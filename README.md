# ChatGPT_React_Summarizer
This bash script is designed to summarize the directory tree and contents of JavaScript (.js), CSS (.css), and other specified files within the ./src directory and its subdirectories. The resulting output.txt file can be copied and pasted into a ChatGPT (or other AI) prompt for code analysis and enhancements with ChatGPT.

## Usage
To use this script, follow these steps:

* Open a bash prompt.
* Navigate to the base directory (../src) of your project and copy doit to there. You may have to set permissions (e.g. chmod 755 doit).
* There are 2 options now:

1) **Summarizing All .js and .css Files**: Run the doit script by executing the command ./doit --all.
The script will generate the output.txt file, which contains a tree summary and the contents of each JavaScript and CSS file.  

2) **Summarizing Specific Files**: Run the doit script specifying the files you want to process, e.g., ./doit --file_list App.js App.css src/foo.html.  The script will generate the output.txt file, which contains a tree summary and the contents of the specified files.

* Finally, copy/paste the copied content into a ChatGPT (or other AI) prompt for code analysis and development.

## Verified Systems
This script has been tested and verified to work on the following system:

* GitBash on Windows 10


## Acknowledgements

This script was co-developed with ChatGPT, an AI-powered language model that assists in code analysis and development tasks.
