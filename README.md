# KateEditor-PlantUML
`KateEditor-PlantUML`,  is a `syntax` highlighter for the `Kate Editor`, designed specifically for `PlantUML`.

## Install :
To install it, you should copy `PlantUML.xml` to the `Kate` syntax folder, depending on your operating system, following the correct path for yourself.

## Unix/Linux
Please add the `PlantUML.xml` file to the path provided below:


```Bash
# For all users  
/usr/share/katepart5/syntax

# For current user
$HOME/.local/share/katepart5/syntax

or

$HOME/.local/share/org.kde.syntax-highlighting/syntax

```
>Note: If either the directory `katepart5` or `org.kde.syntax-highlighting` does not exist in the `$HOME/.local/share/` path, you must create one.

>Note: Additionally, if the directory syntax does not exist in either the `/usr/share/katepart5/` or `$HOME/.local/share/katepart5/` path, you must create one.

## Windows 
Please add the `PlantUML.xml` file to the path below.

```Bash
%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax
```
>Note : If the directory `syntax` does not exist, you must create one in this path: `%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/`.

>Note : `%USERPROFILE%/` in Windows is a short path for `C://User/[yourusername]`
