FROM parity/parity:v2.7.2-stable
COPY . /Settings/Ethereum/PrrofOfAutority/node.pwds /Settings/Ethereum/PrrofOfAutority/spec.json /Settings/Ethereum/PrrofOfAutority/config.toml /home/parity/.local/share/io.parity.ethereum/
CMD ["--base-path","."]
ENTRYPOINT ["/bin/parity"]  