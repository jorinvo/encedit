# encedit

This script helps you editing encrypted files to store some secret information.
This can be used as a lightweight alternative to cloud solution like LastPass.



    Usage: ./encedit <filename>

    Edit an encrypted file with your default editor and save it back automatically.


    To create an encrypted file use:

        openssl enc -aes-256-cbc -salt -in <filename> -out <enc-filename>







## License

[MIT](https://github.com/jorinvo/encedit/blob/master/LICENSE.txt)
