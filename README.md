# DxPool-Ironfish-Miner

Current Iron Fish mining software only supports **NVIDIA GPUs** on **Linux** system,  **Windows** ,  **AMD** , and **mineros** miner will come out in the near future.

## **Preparation Before Mining**

IRON mining at DxPool requires a Iron Fish account, to acquire one: [Create an account | Iron Fish](https://ironfish.network/docs/onboarding/new-account-iron-fish).

Check miner, network, and electricity condition.

## **Configure Your Mining Device**

Your miner must be connected to the DxPool server listed below for your hashrate and revenue to be recorded and monitored.

You’ll need to enter the following information in your mining software:

* Edit the "config" file by inputing information as listed below.

```json
{
  "loglevel": -1,
  "miners": [
    {
      "cryptoname": "ironfish",
      "minername": ["gpu"],
      "pool": {
        "host": "ironfish.ss.dxpool.com",
        "port": 8899,
        "user": "0000",
        "pass": "x"
      }
    }
  ]
}
```

Make sure you have enetered your wallet address for the "User" bar.

* Open "command terminal" , then open software-located file, unzip "dxpoolminer" file and place it at the same file location with the "config" file.
* Imput "chmod -x dxpoolminer" and ./dxpoolminer; start running.

```shell
unzip dxpoolminer.zip

chmod 777 dxpoolminer

./dxpoolminer
```

#### To Stop Mining

Press "Ctrl"+"C", "Q", or "ESC" to stop the miner

## **Start Mining Today**

Your machines are now ready to mine!

As long as you’re submitting your hashrate successfully, you will receive payouts from DxPool.

To view your real-time IRON payout records, visit the [DxPool website](https://www.dxpool.com/pool/kda/miner) and enter your wallet address.

## **Withdrawing Payouts**

[**Auto withdrawal**](https://www.dxpool.com/help/en/auto-withdraw)**： **System will automatically withdraw your payouts on UTC+8 10:00 every day.
