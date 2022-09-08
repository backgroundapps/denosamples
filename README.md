# fresh project

### Setup

.1 First install deno by adding on terminal the following command: 
    curl -fsSL https://deno.land/install.sh | sh
.2 Then add Deno on path, on way is following the step bellow:
    - open the .bashrc typing "vim ~/.bashrc"
    - elable the insert mode by pressing the key "i"
    - go to the end of the file and add the following lines
        export DENO_INSTALL="/home/gitpod/.deno"
        export PATH="$DENO_INSTALL/bin:$PATH"
    - save and exit the editor pressing ESC, followed by typing :wq and ENTER
.3 After this test DENO by typing the following command
    - deno run https://deno.land/std@0.154.0/examples/welcome.ts
    - This command will print a Welcome message
.4 Now go to the fresh page and run the folloing command:
    - deno run -A -r https://fresh.deno.dev my-project
    - For testing reason enter on the created folder with cd my-project and run the following command
    - deno task start


### Usage

Start the project:

```
deno task start
```

This will watch the project directory and restart as necessary.
