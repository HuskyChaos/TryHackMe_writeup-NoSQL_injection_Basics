<h1>TryHackMe - NoSQL injection Basics</h1>
<img src="./img/logo.png" alt="logo" width="400">
<ul>
    <li>
        <h3>Task 1:</h3>
        <ol type="1">
            <li>
                <strong>A group of documents in MongoDB is known as a...</strong><br>
                <code>collection</code>
            </li>
            <li>
                <strong>Using the MongoDB Operator Reference, find an operator to filter data when a field isn't equal to a given value</strong><br>
                <code>$ne</code>
            </li>
            <li>
                <strong>A group of documents in MongoDB is known as a...</strong><br>
                <code>0</code>
            </li>
        </ol>
    </li>
    <li>
        <h3>Task 3:</h3>
        <ol type="1">
            <li>
                <strong>When bypassing the login screen using the $ne operator, which user are you logged in as?</strong>
                <ul>
                    <li>
                        Start Machine<br>
                        <img src="./img/startMachine.png" alt="startMachine" width="600">
                    </li>
                    <li>Open the ip on browser</li>
                    <li>
                        Turn on burpsuite to intercept the login request.
                    </li>
                    <li>Enter random values inside input field and subimt.</li>
                    <li>
                        Switch to burpsuite where the request is intercepted <br>
                        <img src="./img/burpsuite1.png" alt="burpsuite1" width="500">
                    </li>
                    <li>
                        Add <code>[$ne]</code> after <code>user</code> and <code>password</code><br>
                        <img src="./img/burp2.png" alt="burp2" width="500">
                    </li>

                </ul>
            </li>
        </ol>
    </li>
</ul>