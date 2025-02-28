<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hack n' Seek</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Hack n' Seek</h1>
        
        <h2>Challenge Description:</h2>
        <p>In your goal of becoming a skilled penetration tester, you decided to try your hand at bug bounties.<br>
        Browsing through the bug bounties that you received, you noticed one in particular that seemed like an excellent way to start the day.<br>
        The target was a WordPress site that appears to have a slightly outdated version.</p>
        
        <h3>Your goals</h3>
        <ul>
            <li>☛ Full exploitation of the vulnerability is not part of the challenge.</li>
            <li>☛ Search for a critical vulnerability in the WordPress site.</li>
            <li>☛ Read about the vulnerability to understand from where the issue originated.</li>
            <li>☛ Navigate to the page with the vulnerable code to reveal the flag.</li>
        </ul>
        
        <h2>Process:</h2>
        <p>Notice the version of the site in the lower footer 'This website is powered by WordPress core 4.6'.<br>
        Search online for 'wordpress 4.6 vulnerability' and one of the first sites you will find will be this one:<br>
        <a href="https://exploitbox.io/vuln/WordPress-Exploit-4-6-RCE-CODE-EXEC-CVE-2016-10033.html" target="_blank">WordPress 4.6 RCE CVE-2016-10033</a></p>
        
        <p>Scroll down to "IV. DESCRIPTION".<br>
        From the text, copy the following snippet <code>'wp-includes/pluggable.php'</code> and paste it into the URL of the challenge site.<br>
        Press enter and you will receive the flag.</p>
        
        <details>
            <summary>Hidden Flag</summary>
            <p>08f60ae5cf4500ccc86a0601c34855ce</p>
        </details>
    </div>
</body>
</html>
