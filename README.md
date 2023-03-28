# Serverless Stack Extended Backend Resources
We create a [property listing](https://alaqari.co) from scratch. This repository is used to orchestrate the required services for our backend.

#### Usage
To use this repo locally you need to have the [Serverless framework](https://serverless.com) installed.

``` bash
$ npm install serverless -g
```

Clone this repo.
``` bash
$ git clone https://github.com/mraheel83/serverless-stack-resources.git
```

Go to one of the services in the `service` directory and run this to deploy to AWS account.
``` bash
$ serverless deploy -v
```

If you would like to remove the specific resources stack then Go to one of the services in the `service` and run this.
``` bash
$ serverless remove -v
```
