Assignment 2 – Storage Configuration on AWS

Description
In this experiment, Amazon S3 storage service was configured. A new S3 bucket was created. Files were uploaded to the bucket, downloaded successfully, and deleted to understand storage management in cloud computing.

Services Used
Amazon S3 (Simple Storage Service)

Configuration Details
Bucket Name: my-demo-bucket
Region: Default
Storage Type: Standard
Operations Performed: Upload, Download, Delete

🛠 What You Will Do in This Lab -
You will:
1️⃣ Create a pipe
2️⃣ Create a child process using fork()
3️⃣ Parent writes message
4️⃣ Child reads message
5️⃣ Print output

Result
The storage service was successfully configured, and data operations were performed successfully on AWS S3.

Learning Outcome
Understood how object storage works in cloud computing and how AWS S3 manages data securely and efficiently.


📌 What is IPC (Inter Process Communication)?
IPC is a mechanism that allows two or more processes to communicate and share data.

In Linux, built-in IPC mechanisms include:
POSIX
FIFO (Named Pipe)
FUTEX
System V IPC
Pipes

🎯 What is a Pipe?
A pipe is a communication channel between two processes.

Think like this:
Process A ➜ writes data
Pipe ➜ carries data
Process B ➜ reads data
It works like a water pipe 🚰

1️⃣ pipe(fd);
Creates communication channel.
fd[0] → Read end
fd[1] → Write end

2️⃣ fork();
Creates a new child process.
Now we have:
Parent process
Child process

3️⃣ Parent Writes
Parent:
Closes read end
Writes message into pipe

4️⃣ Child Reads
Child:
Closes write end
Reads message from pipe
Prints it

🧪 How To Run (Linux Terminal)
Step 1:
gcc pipe.c -o pipe
Step 2:
./pipe
Output:
Child received: Hello from Parent!

