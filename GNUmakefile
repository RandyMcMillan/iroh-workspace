cargo-build-all:
	for t in */Cargo.toml;  do echo $$t; cargo build -vv --manifest-path $$t; done
cargo-test-all:
	for t in */Cargo.toml;  do echo $$t; cargo test -vv --manifest-path $$t; done
cargo-install-all:
	for t in */;  do echo $$t; cargo install --bins -vv --path $$t; done
