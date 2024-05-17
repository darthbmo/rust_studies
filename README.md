# rust_studies
## This repository is only to register topics studied in rust language.
* Installing Rust in Linux Distro:
  - open the Terminal (console/konsole) and execute the next command line: $ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
    - the $ in terminal indicate common user;
    - curl is command line which allow transfer data;
    - --proto is a option which indicate what is protocol used to transfer data. Example: '=https'. secure http;
    - --tlsv1.2 force the curl to use tls1.2 or later when connecting to a remote server TLS;
    - https://sh.rustup.rs conect to server and execute the rust file, file with extension .rs;
      - then will be installed the lastet stable version of rust. You might be prompted for your password;
      - If is ths installation is successfull, will be shown on the terminal the next message: "Rust is installed now. Great!";
    - the option -sSf...
    - the | sh means that the exit will be redirected to terminal sh;
