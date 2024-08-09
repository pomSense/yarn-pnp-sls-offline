# A Reproduction Repo for Yarn PnP + Serverless Offline

Pull the repo and run `yarn` to install the dependencies.

**Working Scenario:**

Works with `serverless offline start --useInProcess`. Simply do:
```
yarn works
```

Open postman, and make any request to `http://localhost:4400`.


**Failing Scenario:**

Fails when `--useInProcess` is not used. Simply do below or `serverless offline start`:
```
yarn fails
```

Open postman, and make any request to `http://localhost:4400`.