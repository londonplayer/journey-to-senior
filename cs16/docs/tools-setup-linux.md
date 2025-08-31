# Linux Environment Setup

## Packages
```bash
sudo apt-get update
sudo apt-get install -y build-essential clang gdb valgrind cmake make git curl \
  tcpdump wireshark tshark linux-tools-common linux-tools-generic strace perf \
  iperf3 jq python3 python3-venv python3-pip gnuplot graphviz libssl-dev
```

## Python
```bash
python3 -m venv ~/.venvs/cs16
~/.venvs/cs16/bin/pip install numpy scipy matplotlib scikit-learn pytest hypothesis
```

## Nand2Tetris + Simulators
- Download Nand2Tetris tools; ensure `HardwareSimulator.sh` and `CPUEmulator.sh` run.
- Install logisim-evolution (AppImage or package).
- Circuit sim: Falstad (browser) or LTspice.

## Coq + nuXmv (Week 11)
```bash
sudo apt-get install -y opam
opam init -y
opam switch create 4.14.2 -y
opam install -y coq coqide
```
Download nuXmv binary and add to PATH.

## Perf flame graphs
- Clone Brendan Gregg’s FlameGraph repo.