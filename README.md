# Linux-Commands

<h2>Table of Contents</h2>
<ul>
  <li><a href="#ls">ls</a></li>
  <li><a href="#pwd">pwd</a></li>
  <li><a href="#mkdir">mkdir</a></li>
  <li><a href="#rmdir">rmdir</a></li>
  <li><a href="#touch">touch</a></li>
  <li><a href="#cd">cd</a></li>
  <li><a href="#cd ..">cd ..</a></li>
  <li><a href="#ls -a">ls -a</a></li>
  <li><a href="#ls -l">ls -l</a></li>
  <li><a href="#mv oldname.txt newname.txt">mv oldname.txt newname.txt </a></li>
  <li><a href="#mv file.txt /home/user/docs/">mv file.txt /home/user/docs/</a></li>
  <li><a href="#cp source.txt destination.txt">cp source.txt destination.txt</a></li>
  <li><a href="#sudo chmod -R 777 path ">sudo chmod -R 777 path </a></li>
  <li><a href="#find /home/user -name "*.txt">find /home/user -name "*.txt"</a></li>
  <li><a href="#curl">using curl</a></li>
  <li><a href="#sudo apt update">sudo apt update</a></li>
  <li><a href="#sudo reboot">sudo reboot</a></li>
  <li><a href="#zip dharani.zip dharani.txt">zip dharani.zip dharani.txt</a></li>
  <li><a href="#unzip dharani.zip">unzip dharani.zip</a></li>
  <li><a href="#open">open</a></li>
  <li><a href="#clear">clear</a></li>
  <li><a href="#nano">nano</a></li>
  <li><a href="#whoami">whoami</a></li>
  <li><a href="#grep [options] pattern [file]">grep [options] pattern [file]</a></li>
</ul>


<h2 id="ls">ls</h2>
<p>Lists files and directories in the current directory.</p>
<pre><code>ls</code></pre>

<h2 id="pwd">pwd</h2>
<p>Displays the current working directory.</p>
<pre><code>pwd</code></pre>

<h2 id="mkdir">mkdir</h2>
<p>Creates a new directory.</p>
<pre><code>mkdir /directory-path/directory-name</code></pre>

<h2 id="rmdir">rmdir</h2>
<p>Removes an empty directory.</p>
<pre><code>rmdir /director-path/directory-name</code></pre>

<h2 id="touch">touch</h2>
<p>Creates an empty file or updates the timestamp of an existing file.</p>
<pre><code>touch file-name</code></pre>

<h2 id="cd">cd</h2>
<p>Changes the current working directory.</p>
<pre><code>cd /directory-path</code></pre>

<h2 id="cd ..">cd ..</h2>
<p>Moves one directory up.</p>
<pre><code>cd ..</code></pre>

<h2 id="ls -a">ls -a</h2>
<p> Lists all files, including hidden files.</p>
<pre><code>ls -a</code></pre>

<h2 id="ls -l">ls -l</h2>
<p>Lists files in long format with detailed information.</p>
<pre><code>ls -l</code></pre>

<h2 id="rmdir">Renaming</h2>
<p>Renames a file.</p>
<pre><code>mv oldname.txt newname.txt</code></pre>

<h2 id="rmdir">To move</h2>
<p>Moves a file to a different directory.</p>
<pre><code>mv file.txt /directory-path-we-want-to-move</code></pre>

<h2 id="rmdir">Copy File</h2>
<p>Copies a file from one location to another.</p>
<pre><code>cp source.txt destination.txt</code></pre>

<h2 id="rmdir">Copy Directory</h2>
<p>Copies the entire directory /source_dir and its contents (including subdirectories) to /dest_dir</p>
<pre><code>cp -r /source_dir /dest_dir</code></pre>

<h2 id="rmdir">File Permission</h2>
<p> Changes file permissions recursively to allow full read, write, and execute access to all users.</p>
<pre><code>sudo chmod -R 777 /path</code></pre>

<h2 id="rmdir">Find Files</h2>
<p>Finds files with a specific pattern in a directory.</p>
<pre><code>find /path -name "*.txt" </code></pre>

<h2 id="rmdir">Curl</h2>
<p>Downloads a file from a URL.</p>
<pre><code>curl -O http://example.com/file.zip</code></pre>

<h2 id="rmdir">Update packages</h2>
<p>Updates the package list on Ubuntu/Debian-based systems. </p>
<pre><code>sudo apt update</code></pre>

<h2 id="pwd">Restart</h2>
<p>Reboots the system.</p>
<pre><code>sudo reboot</code></pre>

<h2 id="pwd">Compress as Zip file</h2>
<p>Compresses a file into a zip archive.</p>
<pre><code>zip [zip-name] [the-file-name-you-want-to-compress]</code></pre>

<h2 id="pwd">Extract Zip File</h2>
<p>Extracts files from a zip archive.</p>
<pre><code>unzip [zip-file-name]</code></pre>

<h2 id="pwd">Open</h2>
<p>Open a file.</p>
<pre><code>open filename</code></pre>

<h2 id="pwd">clear</h2>
<p>The clear command is used to clear the terminal screen</p>
<pre><code>clear</code></pre>

<h2 id="pwd">nano</h2>
<p> it opens for editing. If it doesn't exist, nano creates a new file.</p>
<pre><code>nano file-name</code></pre>

<h2 id="pwd">whoami</h2>
<p>It print the current username</p>
<pre><code>pwd</code></pre>

<h2 id="grep [options] pattern [file]">grep [options] pattern [file]</h2>
<p>The grep command searches for a specific pattern (text) within files or output and displays matching lines.</p>
<pre><code>grep "hello" file.txt</code></pre>
