## V Cloud Basic User's Manual （v0.1.1）
### Login

The V-Cloud service provides two ways to login: Google account and Github account. The email address from the login account will be associated with the V-Cloud account. If the email from both Google account and Github account are the same, they will be associated with the same V-Cloud account. (__Attention:__ If the first time logging in of Github account does not contain an email address, it will not be associated with any previous Google account further on.)

### Compute Cloud
##### Before start
Currently, only Ubuntu operating systems is supported. You can find more information in Ubuntu [documentation](https://ubuntu.com/server/docs).
 - [Ubuntu Server 18.04 LTS](https://wiki.ubuntu.com/BionicBeaver/ReleaseNotes#Ubuntu_Server)
 - [Ubuntu Server 16.04 LTS]()

##### Start an instance

1. Create an key pair in V-Cloud and save it. **Don't give your key pair to any one**
2. Launch your instance. You can connect to your instance when the status is running

##### Connect to your instance
   - On Linux/macOs
      1. Change file permission of the private key file you saved to 600
      2. Set your ssh config at `~/.ssh/config` or through `ssh -i`.

   - On Windows
      Use your favorite ssh client (such as [Putty](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html), [SecureCRT](https://www.vandyke.com/products/securecrt/) ) to do the ssh connection.

##### Terminate your instance

​	Click the terminate button on the row of instance you want to terminate. Once you terminate your instance, the ip address of it will never be back.

### Token Service

If you are an issuer of token (on v.systems chain), you can quickly create wallet and explorer for your token on v-cloud platform. Once your application is verified, the wallet and explorer will be deployed to your custom domain.

