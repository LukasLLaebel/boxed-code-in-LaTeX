# boxed-code-in-LaTeX
> Beautiful code blocks in LaTeX — easy setup, customizable syntax highlighting for Python, SQL, Java, JavaScript, C, C++, and C#.

## Features
- Clean, modern code blocks for LaTeX documents
- Predefined styles for multiple programming languages
- Quick installation with `.sty` file

## Installation
> Copy blockcoding.sty to your local LaTeX directory (make one if missing!). (For MiKTeX: *C:\Users\Username\AppData\Local\Programs\MiKTeX\tex\latex\local\*)
and
> Open MiKTeX Console → Tasks → Refresh File Name Database.

Add to your LaTeX document.
```tex
\usepackage{blockcoding}
```

## Example for Tex file
```tex
\begin{sourcecode}[java]
  // Example of a Java class
  public class HelloWorld {
      public static void main(String[] args) {
          // Print a greeting
          System.out.println("Hello, World!");
      }
}
\end{sourcecode}
```

## Troubleshooting
> Can't find the installation path?
> Try compiling a document with any package.
> Then check your LaTeX log file — it will show where packages are being loaded from.
