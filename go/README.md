# Getting started in Go

1. If you have not already done so, follow the Google Genomics [sign up instructions](https://cloud.google.com/genomics/install-genomics-tools#authenticate) to generate and download a valid ``client_secrets.json`` file.  Save the "client ID" and "client secret" values from the credential.

2. [Install go](http://golang.org/doc/install)
(make sure you set up a [$GOPATH](https://code.google.com/p/go-wiki/wiki/GOPATH))

3. Get the client library and oauth dependencies.
(Note: this will [require mercurial](http://golang.org/s/gogetcmd))

    ```
    go get google.golang.org/api/genomics/v1beta2
    go get code.google.com/p/goauth2/oauth
    ```

4. Run the code:

    ```
    go run main.go client_id client_secret
    ```
