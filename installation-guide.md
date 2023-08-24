# Installation Guide: GitHub Desktop on Linux

This guide will walk you through the process of installing GitHub Desktop on Linux.

## Prerequisites

- Ubuntu-based Linux distribution
- Terminal access

## Installation Steps

1. Open a terminal using 

    `Ctrl + Alt + T`.

2. Download the GitHub Desktop .deb package:

    ```
    $ sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.8.1-linux2/GitHubDesktop-linux-2.8.1-linux2.deb
    ```

3. Once the download is complete, navigate to the download directory:

    ```
    $ cd ~/Downloads
    ```

4. Install GitHub Desktop using dpkg:

    ```
    $ sudo dpkg -i GitHubDesktop-linux-2.8.1-linux2.deb
    ```

5. Launch GitHub Desktop from the application menu.

    **Verification**

    To confirm that GitHub Desktop is installed, open the application menu and search for GitHub Desktop. 

    You should see the icon and be able to launch it.

    ![Alt text](image.png)

    Congratulations, you have successfully installed GitHub Desktop on your Linux system!

6. Adding GitHub Desktop to favorites

    Right-click on the GitHub Desktop icon and select "Add to Favorites" to easily access it.

    ![Alt text](image-2.png)

7. Now you are ready to go! Enjoy using GitHub Desktop for your repositories.

    ![Alt text](image-1.png)

    Happy Coding!

<script>
function copyToClipboard(buttonId, targetId) {
    const commandText = document.getElementById(targetId).textContent;
    const tempInput = document.createElement('textarea');
    tempInput.value = commandText;
    document.body.appendChild(tempInput);
    tempInput.select();
    document.execCommand('copy');
    document.body.removeChild(tempInput);
    const button = document.getElementById(buttonId);
    button.textContent = 'Copied!';
    setTimeout(() => {
        button.textContent = 'Copy';
    }, 1500);
}
</script>
<button onclick="copyToClipboard('copyButton1', 'command1')">Copy</button>
<button onclick="copyToClipboard('copyButton2', 'command2')">Copy</button>
<button onclick="copyToClipboard('copyButton3', 'command3')">Copy</button>
<button onclick="copyToClipboard('copyButton4', 'command4')">Copy</button>
