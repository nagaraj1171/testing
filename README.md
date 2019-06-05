##*README.md*

This script extracts the IP address from the json files as provided in the example.

The script takes one json file as an input. To get help please pass -h or --help.

###Steps to run this script as a command.

1. grant execute rites on the file
    ```sh
       $ chmod +x ip_print
    ```
1. Make sure you have rite interpreter in the shebang of the file
    ```bash
    #!/usr/bin/env python3
    ```

1. Export the path of the file in PATH variable using the below command
    ```sh
        $ export PATH=$PATH:<path_to_the_script>
    ```

### How to run the script

```bash
$ ip_print FILENAME
```

###To seek help
```bash
$ ip_print -h
```

> The best approach is to package the script as a yum or debian package.
> This approach is for demo only.