---


---
[![Build](https://github.com/Graqr/Augr/actions/workflows/maven.yml/badge.svg)](https://github.com/Graqr/Augr/actions)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Graqr/Augr)
![GitHub](https://img.shields.io/github/license/Graqr/Augr)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/Graqr/Augr/main)
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/y/Graqr/Augr)

## Summary


### Install

<details><summary>Windows</summary>
    <ol>
        <li>Download latest windows binary</li>
        <li>Move executable to dedicated directory, ie <code>"C:\Program Files\Jonathan is so cool\"</code></li>
        <li>Add directory to your PATH</li>

```PowerShell
"C:\Program Files\my-directory\" |
if (!($env:Path -like "*$_*"))
{
    $env:Path = "$( $env:Path );$_"
}
```

</ol>
</details>

<details><summary>Linux</summary>
<ol>
        <li>Download latest linux binary</li>
        <li>Add to <code>$HOME\bin\</code> directory</li>
</ol>
</details>

___



### Want to get involved? 
 See our [contributing] doc before taking a whack at any [open issues].
 
[contributing]:Contributing.md
<!--TODO: update to new repo name post clone -->
[open issues]:https://github.com/Graqr/Augr/issues?q=is%3Aopen+is%3Aissue 
