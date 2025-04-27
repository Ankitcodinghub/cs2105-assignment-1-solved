# cs2105-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2105 Assignment 1 Solved](https://www.ankitcodinghub.com/product/cs2105-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121428&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2105 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Objectives

In this assignment, you will implement a server that communicates with clients using an HTTP-like protocol. After completing this assignment, you should (1) be able to implement a simple TCP-based server, and (2) have a good understanding of the mechanisms of HTTP.

Group Work

Grading

We will test and grade your program on the stu server. Please make sure that your program run properly on stu. Moreover, you are allowed to use libraries installed in public folders of stu (e.g. /usr/lib) only.

We accept submission of Python 3 (in particular, 3.8), Java, or C/C++ program, and we recommend that you use Python 3 for your assignments. Programming languages other than Python 3, Java, and C/C++ are not allowed. For Python 3, we use the python3 program installed in folder /usr/bin on stu for grading. If you use Java or C/C++, we will compile and run your program for grading using the default compilers on stu (openjdk 17 installed in /usr/local/jdk/bin, or gcc 9.4.0 installed in /usr/bin).

The grading script infers your programming language from the file extension name (.py, .java, .c). Therefore, please ensure your files have the correct extension names. For a Java program, the class name should be consistent with the source file name, and please implement the static main() method so that the program can be executed as a standalone process after compilation. We will deduct 1 mark for every type of failure to follow instructions (e.g. wrong program name).

Note that for Java programs, name your main class as WebServer and hence source file name WebServer.java during development. When you want to test your program using the provided script on stu server, or to make submission, rename your file name according to program submission and group submission section while keeping the class name as WebServer. Grading script will rename your file accordingly during compilation.

We will grade your program based on its correctness only. A grading script will be used to test your program and no manual grading will be provided.

Testing Your Program

To test your program, please use your SoC UNIX ID and password to log on to stu as instructed on Assignment 0 paper. Your server program should receive one commandline argument which is the port number to listen(), as the following command shows: python3 WebServer-A0165432X.py &lt;port&gt;

If you test your server manually, please select a port number greater than 1024, because the OS usually restricts usage of ports lower than 1024. If you get a BindException: Address already in use (or similar errors for other languages), please try a different port number. Note that your program should not read from stdin. Your program can print anything to stdout or stderr, and our test script will silently ignore them.

To use the grading script, please upload your program and all .so files along with the test folder given in the package to stu. Make sure that your program, the .so files, and the test folder are in the same directory. Then, you can run the following command to test your server program: bash test/WebServer.sh

By default, the script runs through all test cases. You can also choose to run a certain test case by specifying the case number in the command: bash test/WebServer.sh 3

To stop a test, press ctrl-c. If pressing the key combination once does not work, hold the keys until the script exits.

If you ever encounter this error: tput: unknown terminal “xterm-256color” when testing your program using script provided, run export TERM=xterm once after you log in and before you run WebServer.sh.

There is a low possibility that the grading script is grading an existing running server program instead of yours, if they use same port. So start the assignment early to avoid “congestion” during last few days. An advice to ensure the grading feedback you received is on your current program is to print to screen your student number right after receiving a connection, and kill your own existing server programs if any before testing it again. The grading result will be based on your program if you see your student number printed for particular test case, or otherwise try again.

Program Submission

For individual submission, please name your single source file as WebServer-&lt;Matric number&gt;.py and submit it to the Assignment_1_student_submission folder of LumiNUS Files. Here, &lt;Matric number&gt; is your matriculation number which starts with letter A. An example file name would be WebServer-A0165432X.py. If you use Java, C, or C++ to implement the web server, please use .java, .c, or .cpp respectively as the extension name. Note that file names are case-sensitive on stu.

You are not allowed to post your solutions to any publicly accessible site on the

Internet.

Special Instructions for Group Submission

For group submission, please include matriculation numbers of both students in the file name, i.e. WebServer-&lt;Matric number 1&gt;-&lt;Matric number 2&gt;.py. Submit it to the same Assignment_1_student_submission folder. An example file name would be WebServer-A0165432X-A0123456Y.py. For each group, there should be one designated member who submits the file, to avoid problems caused by multiple branches within a group. Do not change the designated submitter! If the group needs to upload a new version, it should be done by the same designated submitter as well.

You are free to discuss this assignment with your friends. However, you should refrain from sharing your program, program fragments, or detailed algorithms with others. If you want to solve this assignment in a group, please do so and declare it as group work.

Question &amp; Answer

If you have any doubts on this assignment, please post your questions on LumiNUS forum before consulting the teaching team. However, the teaching team will NOT debug programs for students and we provide support for language-specific questions as a best-effort service. The intention of Q&amp;A is to help clarify misconceptions or give you necessary directions.

The Server

In this assignment, you are required to implement a HTTP-like server that provides key-value store services. The server consists of two components. The first is a custom protocol simplified from HTTP 1.1. It retains the basic request-response mechanism and the persistent connection feature of HTTP 1.1, but uses a different header format. On top of this protocol, an interactive in-memory key-value store with a counter store are to be implemented under the path /key/ and /counter/ respectively. The keyvalue store supports insertion, update, retrieval, and deletion operations on key-value pairs. In addition, a record can be marked as temporary by adding a counter with the corresponding key in the counter store. The counter represents the remaining retrieval times of a temporary record in the key-value store. It will be decreased by 1 for each retrieval of the record in key-value store. A record in key-value store without a counter can be retrieved/updated with arbitrary times. In contrast, a temporary record is readonly and will be deleted after the corresponding counter reaches 0. Figure 1 shows the overall architecture of the web server.

Figure 1: The layered architecture of the server. You need to implement the top two layers which are highlighted with bold fonts.

The TCP Socket

The lowest-level layer of this server is the TCP socket interface. Basically, the server should

1. bind() to a port

2. listen() to the socket and accept() a new connection

3. Parse and respond to client request(s) sequentially, by using recv() and send() for socket I/O.

4. Going back to 2 after the client disconnects

As discussed in the “Testing Your Program” section, port number is passed to your server as a command line argument. The grading script ensures that only one client connects to your server at any time so that no connection multiplexing or polling is required; your server can simply process connections sequentially.

It is necessary to detect disconnection events reliably, because your server is required to support the persistent connection feature originated from HTTP 1.1. If the bytes object returned by recv() is of zero length, then no more data could be recv()’ed from the connection. Since this only indicates half close (from client side only) of a TCP connection, your server should finish processing the final request(s) before closing the connection on server side. The client is guaranteed to keep the connection half open until either the server finishes sending all responses or a timeout occurs. Therefore, there will be no send() failures on the server side, unless it times out during this process.

The HTTP-like Protocol

After establishing a new TCP connection with a client, your server should read a customized HTTP request from the socket, which consists of request headers and an optional request body. Your server parses the request and sends the corresponding response as defined below. After such a request-response cycle, the connection is persistent (i.e. not closing immediately), and the server waits for another request from the same client until a notification of socket disconnection.

Since a real-world TCP connection could be intermittent, your server is also required to work properly when requests are delivered in chunks of random sizes with delays between chunks. Note that a TCP connection only guarantees ordering of data, but not segment sizes or delays. The test script simulates this type of intermittent connection in some test cases, while keeping the delays between two consecutive transfers below one second. To handle chunks that contain incomplete requests, it is sufficient for your server to handle data buffering well.

In addition, your server should be responsive in the sense that upon receiving a complete request, the server processes it and sends back the response immediately. The test script sets an one-second timeout after each request is fully sent to the server. If a single chunk contains multiple requests, your server is also expected to respond quickly to all complete requests inside.

To grasp the core ideas of HTTP, we omit other tedious aspects of the protocol. For this assignment, the server only needs to handle basic request and response information, as well as the Content-Length header field. The header format of this HTTP-like protocol is simplified as follows:

(a) GET␣/key/CS2105␣␣

(b) POST␣/key/CS2105␣Content-Length␣27␣␣Intro␣To␣Computer␣Networks!

(c) POST␣/counter/CS2105␣Content-Length␣1␣␣3

(d) GET␣/key/CS2105␣␣

(e) GET␣/counter/CS2105␣␣

(f) POST␣/counter/CS2105␣Content-Length␣1␣␣2

(g) DELETE␣/key/CS2105␣␣

(h) DELETE␣/counter/CS2105␣␣

(i) GET␣/counter/CS2105␣␣

(j) DELETE␣/key/CS2105␣␣

4. For a response, the first two substrings (compulsory) are HTTP status code and description of status. The description has no real effects and is kept as a convention as in HTTP, and it should not have any spaces. If the response has a content body, a Content-Length header should similarly be included, if there’s content body. The corresponding changes of state in the server are shown in Figure 2 and responses for the above 10 requests could be:

(a) 404␣NotFound␣␣

(b) 200␣OK␣␣

(c) 200␣OK␣␣

(d) 200␣OK␣Content-Length␣27␣␣Intro␣To␣Computer␣Networks!

(e) 200␣OK␣Content-Length␣1␣␣2

(f) 200␣OK␣␣

(g) 405␣MethodNotAllowed␣␣

(h) 200␣OK␣Content-Length␣1␣␣4

(i) 200␣OK␣Content-Length␣8␣␣Infinity

(j) 200␣OK␣Content-Length␣27␣␣Intro␣To␣Computer␣Networks!

CS2105:

Intro To…

CS2105: 3

Key-value store Counter store Key-value store Counter store

Key-value store Counter store Key-value store Counter store Key-value store Counter store

CS2105:

Intro To…

CS2105: 2

CS2105:

Intro To… CS2105: 4

f

Figure 2: State of Key-value store and Counter store under the 9 consecutive requests.

The Key-value Store and Counter Store

The counter store is very similar to key-value store, except that it stores positive remaining times for the retrieval, instead of bytes value, of a particular key in key-value store. It supports operations that are highly correlated with the key-value store: Insertion – which inserts a key to mark as temporary and the counter which indicates the number of retrieval times that this temporary record has remaining, e.g. (c), Update which increases the existing counter value by certain positive integer, e.g. (f) Retrieval – which allows the client to retrieve the type of the key by getting it from the counter store which returns either the key is not found, positive counter of the temporary key, or a string value Infinity for a permanent key, e.g. (e) (i), and Deletion – which changes the temporary record back to permanent by deleting the counter in the counter store, e.g. (h). Counter keys are a subset of keys in key-value store i.e. only temporary keys should appear in the counter store. The content-length header and a positive integer content should be present in a POST.

Specifications

The key-value store should be accessible to the client through paths with prefix /key/. To operate on a specific key, the complete HTTP path is /key/ appended with the actual key string. For example, a request to operate on key CS2105 specifies /key/CS2105 as the HTTP path. The server should support the following key-value operations over the HTTP-like protocol:

1. Insertion and update

(a) The HTTP request method should be POST and the value to be inserted (or updated) constitutes the content body. There should also be a ContentLength header indicating the number of bytes in the content body.

(b) For insertions, the server should always respond with a 200 OK status code after successfully inserting the key-value pair. For updates, one of two possibilities will occur.

• If there is a positive number of retrieval times in the counter store for the associated key, then the update request is rejected and will return a 405 MethodNotAllowed code.

• Otherwise, server should always respond with a 200 OK status code after updating the value.

2. Retrieval

(a) The HTTP request method should be GET, and there is no content body.

(b) One of three possibilities will occur.

• If the key does not exist in the key-value store, the server returns a 404 NotFound status code.

• If the key already exists and there is a positive number of retrieval times in the counter store for the associated key, the server should return a 200

OK code, the correct Content-Length header and the value data in the content body. Then, the server should decrease the remaining retrieval times of that key in the counter store by 1. Once the number of retrieval times reaches 0, the server should delete the key from both stores.

• Otherwise, if the key exists and is not in the counter store, the server should return a 200 OK code, the correct Content-Length header and the value data in the content body.

3. Deletion

(a) The HTTP request method is DELETE, and there is no content body.

(b) One of three possibilities will occur.

• If the key does not exist, the server returns a 404 NotFound code.

• If the key exists, but there is a positive number of retrieval times in the counter store for the associated key, then the delete request is rejected and will return a 405 MethodNotAllowed code.

• Otherwise, it should delete the key-value pair from the store and respond with a 200 OK code and the deleted value string as the content body.

The counter store should be accessible to the client through paths with prefix /counter/. To operate on a specific key, the complete HTTP path is /counter/ appended with the actual key string. For example, a request to operate on key CS2105 specifies /counter/CS2105 as the HTTP path. Note the keys in counter store are a subset of the ones in key-value store, i.e. temporary keys should appear in both stores. The server should support the following counter key operations over the HTTP-like protocol for a counter store:

1. Insertion and Update

(b) For insertion, one of two possibilities will occur.

• If the key does not exist in the key-value store, the server returns a 405

MethodNotAllowed code.

• Otherwise, the server should respond with a 200 OK status code after updating the counter.

(c) For updates, the server should increase the existing counter value by a positive integer specified in the request, and the client always expects success status.

2. Retrieval

(a) The HTTP request method should be GET, and there is no content body.

(b) One of three possibilities will occur.

• If the key does not exist, and the key is not found in key-value store, the server returns a 404 NotFound code.

• If the key exists , the server should return a 200 OK code, the correct Content-Length header and the remaining retrieval times for the corresponding key.

• Otherwise, if the key is not found in the counter store, but exists in the key-value store, the server should return a 200 OK code, the correct Content-Length header and a string Infinity.

3. Deletion

(a) The HTTP request method is DELETE, and there is no content body.

(b) If the key does not exist, the server returns a 404 NotFound code. Otherwise, it should delete the key-value pair from the store and respond with a 200 OK code and the deleted counter integer as the content body. The ContentLength header should also be sent accordingly.

Grading Rubric

1. The server program is free from syntax errors and can be successfully executed

(or compiled, for Java/C/C++). (1 mark)

(a) The server parses valid HTTP requests and sends correctly formatted responses.

(b) The server supports persistent connection and correctly processes sequential requests as specified.

(c) The server works properly and responsively over intermittent connections simulated by the test script.

(a) The server supports insertion/update of key-value pairs through the POST method according to the spec.

(b) The server supports retrieval of value by key through the GET method according to the spec.

(c) The server supports removal of key-value pairs through the DELETE method according to the spec.

(d) The server supports insertion/update/retrieval/deletion of counter store according to the spec.
