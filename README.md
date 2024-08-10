<h1>JDBC Java Application</h1>
    
<h2>Description</h2>
    <p>This Java application provides a simple user interface for interacting with a MySQL database. The user can add, update, or delete records in the database via a graphical interface built with AWT.</p>
    
 <h2>Prerequisites</h2>
    <ul>
        <li>Java Development Kit (JDK) installed</li>
        <li>MySQL database installed and running</li>
        <li>MySQL JDBC Driver (Connector/J) added to your classpath</li>
    </ul>

 <h2>Database Setup</h2>
    <p>Before running the application, ensure that you have a MySQL database with the following specifications:</p>
    <ul>
        <li>Database name: <code>mydatabase</code></li>
        <li>Table name: <code>mytable</code></li>
        <li>Table columns:
            <ul>
                <li><code>id</code> (INT)</li>
                <li><code>name</code> (VARCHAR)</li>
                <li><code>age</code> (INT)</li>
            </ul>
        </li>
    </ul>

<h2>How to Run</h2>
    <p>To run the application, follow these steps:</p>
    <ol>
        <li>Ensure that MySQL is running and the database is set up as described above.</li>
        <li>Compile the Java code using the following command:
            <pre><code>javac -cp fmysql-connector.jar;. JDBC.java </code></pre>
        </li>
        <li>Run the compiled class:
            <pre><code>java -cp fmysql-connector.jar;. JDBC.java </code></pre>
        </li>
    </ol>

<h2>Application Interface</h2>
    <p>The application provides a simple graphical interface with fields for Name, Age, and ID. You can add, update, or delete records in the database using the respective buttons. A message label at the bottom of the interface displays the status of the operations.</p>
