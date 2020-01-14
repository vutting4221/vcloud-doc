## Basic User's Manual 
### Login

Login with your Google account or GitHub account. If you have both Google and GitHub account, when emails associated with them are same, you can either login with Google or GitHub into a same v-cloud account.

### Compute Cloud

##### Start an instance

1. Prepare your key pair in v-cloud and save it. **Don't give your key pair to any one**
2. Lanch your instance. You can connect to your instance when the status is running

##### Connect to your instance
   - On Linux/macOs
      1. Change file permission of the private key file you saved to 600
      2. Set your ssh config at `~/.ssh/config` or through `ssh -i`.

   - On Windows
      Use your favorite ssh client (such as [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html), [SecureCRT](https://www.vandyke.com/products/securecrt/) ) to do the ssh connection.

##### Terminate your instance

​	Click the terminate button on the row of instance you want to terminate. Once you terminate your instance, the ip address of it will never be back.

### Token Service

If you are an issuer of token (on v.systems chain), you can quickly build wallet and explorer for your token on v-cloud platform. Once your application is verified, the wallet and explorer will be deployed to your custom domain.

