# 0manup

Is a simple tool, with one purpose: Given an incomplete (or incorrect)
[ZeroInstall](http://0install.net/) feed, it will generate / update
correct <manifest-digest> elements as needed, and update implementation
IDs (if they are manifest-based IDs and the manifest is incorrect).

It requires that any required <archive> or <file> URLs be present as
local files in the current working directory (it won't actually
download files).
