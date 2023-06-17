# Readings Class 03: File Manipulation / System.IO

## Why this topic matters

Stream and file mastering I/O gives developers the abilities they need to efficiently manage data, improve application speed, and strengthen security. It is a foundational ability that is essential to many areas of software development, making it an extremely important topic.

## File and Stream I/O

1. Files and directories:

   - Interaction with files and directories using the System.IO namespace.
   - Working with properties, collections, and search criteria.
   - Handling file paths and naming conventions.

2. Streams:

   - The concept of streams as a sequence of bytes for reading and writing.
   - Abstract base class Stream and its derived classes.
   - Operations like reading, writing, and seeking within a stream.
   - Different types of stream classes for various purposes.

3. Readers and writers:

   - Types for reading encoded characters from streams and writing them.
   - Handling conversion of characters to bytes and vice versa.
   - Commonly used reader and writer classes for different data types and sources.

4. Asynchronous I/O operations:

   - Performing resource-intensive tasks asynchronously to maintain application responsiveness.
   - Using async and await keywords with asynchronous I/O methods.
   - Preventing the blocking of the UI thread.

5. Compression:

   - Compressing and decompressing files and streams.
   - Types in the System.IO.Compression namespace for compression operations.
   - Classes for working with zip archives, deflate algorithm, and gzip data format.

6. Isolated storage:

   - Data storage mechanism providing isolation and safety.
   - Saving application settings or files in a controlled manner.
   - Use of isolated storage when access to user files is restricted.

7. I/O operations in Windows Store apps:

   - Differences and considerations when performing I/O operations in Windows 8.x Store apps.
   - Usage of Windows.Storage namespace for file operations.
   - Handling asynchronous methods and path-based compression.

8. I/O and security:

   - Following operating system security requirements for access control to files and directories.
   - Managing ACLs programmatically.
   - Considerations for Internet or intranet applications and using isolated storage for security purposes.
   - Security checks when constructing a stream and avoiding passing streams to less-trusted code or domains.

## Write to a file

There are different ways to write text to a text file for a .NET app. These classes and methods are typically used to write text to a file:

- StreamWriter contains methods to write to a file synchronously (Write and WriteLine) or asynchronously (WriteAsync and WriteLineAsync).

- File provides static methods to write text to a file such as WriteAllLines and WriteAllText, or to append text to a file such as AppendAllLines, AppendAllText, and AppendText.

- Path is for strings that have file or directory path information. It contains the Combine method and in .NET Core 2.1 and later, the Join and TryJoin methods. These methods let you concatenate strings for building a file or directory path.

## Read and write to a newly created data file

The System.IO.BinaryWriter and System.IO.BinaryReader classes are used for writing and reading data other than character strings. Here's an example

    using System;
    using System.IO;

    class MyStream
    {
      private const string FILE_NAME = "Test.data";

      public static void Main()
      {
          if (File.Exists(FILE_NAME))
          {
              Console.WriteLine($"{FILE_NAME} already exists!");
              return;
          }

          using (FileStream fs = new FileStream(FILE_NAME, FileMode.CreateNew))
        {
            using (BinaryWriter w = new BinaryWriter(fs))
              {
                  for (int i = 0; i < 11; i++)
                  {
                      w.Write(i);
                  }
              }
          }

          using (FileStream fs = new FileStream(FILE_NAME,   FileMode.Open, FileAccess.Read))
          {
              using (BinaryReader r = new BinaryReader(fs))
              {
                  for (int i = 0; i < 11; i++)
                  {
                      Console.WriteLine(r.ReadInt32());
                  }
              }
          }
      }
    }

    // The example creates a file named "Test.data" and writes the integers 0 through 10 to it in binary format.
    // It then writes the contents of Test.data to the console  with each integer on a separate line.
