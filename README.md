# rust-lab-1.3
Exercise from the Rust Course on Coursera, Week 1 Assignment 3.

## What I did:
* I added the rust-analyzer and GitHub Copilot extensions to the devcontainer.json file, so they will automaticall be installed when the container is built.
* I added the Container Tools extention manually, then used the gear icon to add it to the devcontainer.json file
* GitHub Copilot added some other settings for me in devcontainer.json
* Rust Analyzer didn't work until I added a `Cargo.toml` file to the project
* I added a `src` folder and a `main.rs` file to the project, then added some code to `main.rs` to test that everything was working correctly.
* I ran `cargo run` in the terminal to test that everything was working correctly, and it printed "Hello, world!" as expected.

## What could be improved:
* I tried using a Dockerfile to use a `rust:slim-trixie` image, but that left me with an image running as root. I can fix that, but didn't want to take the time to do it right now. 
* I was trying to avoid using `cargo new` to create the project, as that wasn't in the instructions, but it would have saved me some time and effort in setting up the project structure and files.
