# 0manup

Is a simple tool, with one purpose: Given an incomplete (or incorrect)
[ZeroInstall](http://0install.net/) feed, it will generate / update
correct &lt;manifest-digest&gt; elements as needed, and update implementation
IDs (if they are manifest-based IDs and the manifest is incorrect).

It requires that any required &lt;archive&gt; or &lt;file&gt; URLs be present as
local files in the current working directory (it won't actually
download files).
