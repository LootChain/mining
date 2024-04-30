## Mining Software Download and Configuration

You can download the mining software suitable for you from the following link: [cpuminer-opt-yespowersugar-sugarchain](https://github.com/cpu-pool/cpuminer-opt-yespowersugar-sugarchain/releases/tag/1.4)

For example, for Windows, you can follow these steps to configure:

1. Download and extract the mining software from the link above.
2. Create a new file named `start.bat` in the extracted folder.
3. Open the `start.bat` file and copy and paste the following content:

```batch
cpuminer.exe -a cpupower -o stratum+tcp://pool.questchain.io:3032 -u WALLET_NUMBER
pause

```
Replace WALLET_NUMBER with your wallet address.

4.Double-click to run the start.bat file and wait for the mining software to indicate successful joining of our pool.
