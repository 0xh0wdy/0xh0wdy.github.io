---
title: "Go"
---

Command:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>go run file.go </code>
  <span style="margin-left: 10px; color: #555;"># Run the go gile</span>
  <br>
  <code>go build file.go </code>
  <span style="margin-left: 10px; color: #555;"># Build the go file</span>
  <br>
  <code>go build -ldflags "-w -s" </code>
  <span style="margin-left: 10px; color: #555;"># Reduce binary size by 30%</span>
  <br>
  <code>GOOS="linux" GOARCH="amd64" go build file.go </code>
  <span style="margin-left: 10px; color: #555;"># Cross-compiling, GOOS (Operating System) GOARCH (Architecture), Can introduce build constraints through command line, code comments, file suffix naming convention </span>
  <br>
  <code>go doc fmt.Println  </code>
  <span style="margin-left: 10px; color: #555;"># Display documentation on a package, function, method, or variable</span>
  <br>
  <code>go install github.com/path/to/repo@latest </code>
  <span style="margin-left: 10px; color: #555;"># To obtain package source code</span>
  <br>
  <code>go fmt /path/to/package </code>
  <span style="margin-left: 10px; color: #555;"># Automatically formats source code</span>
  <br>
</div>