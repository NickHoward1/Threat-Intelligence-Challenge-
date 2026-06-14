<h1>File & Hash Threat Intelligence</h1>

<b>Question1:</b> What is the SHA256 hash of the file?

<b>Powershell:</b> `cd desktop\.'CTI Files' -> Get-Filehash -Algorithm -sha256 filename`
<b>Mac0S:</b> `cd ~/Desktop/"CTI Files" -> shasum -a 256 filename`
<b>Linux:</b> `cd ~/Desktop/"CTI Files" -> sha256sum filename`
