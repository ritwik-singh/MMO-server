<h1 align="left">MMO Server</h1>

###

<p align="left">Built a MMO server using Asio boost in c++. Implemented a threadsafe queue using mutex lock and a client validation in server for proper communication with many clients.</p>

###

<h3 align="left">Architecture</h3>

###

<p align="left">Server Connection<br><br>1. Asio server accepts connection from different client.<br>2. Reads header after connection.<br>3. Header is passed to incoming threadsafe queue of Server.</p>

###

<p align="left">Client Validation<br><br>Server uses a basic client validation function using a Scramble function in a connection box.</p>

###

<h3 align="left">Message Header</h3>

###

<p align="left">MESSAGES<T> <br><br>----- Header (T ID, SIZE (BYTES) )<br>----- Body</p>

###

<h3 align="left">Tech Stack</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" width="52" alt="cplusplus logo"  />
</div>

###

<h3 align="left"></h3>

###

<h3 align="left">Dependencies</h3>

###

<p align="left">Asio boost</p>

###

<p align="left">Inspired by tutorial - https://www.youtube.com/watch?v=2hNdkYInj4g</p>

###
