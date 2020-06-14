# Martellone Alexa Skill

> Alexa, ask Martellone what does he think about it

![image](./icons/martellone-icon-small.png)

Skill created as a tribute to the mythological [Nando Martellone](https://www.youtube.com/watch?v=l0kKxkulOiI), character of the TV Show [Boris](<https://en.wikipedia.org/wiki/Boris_(TV_series)>).

## Preliminary Steps

Install node dependencies

```sh
npm install
```

Install serverless module globally `npm install -g serverless` or use it via `npx` (i.e. `npx serverless deploy`)

## How to

1. Run `sls alexa auth` to authenticate
2. Run `sls alexa create --name "Martellone" --locale en-GB --type custom` to create a new skill
3. Add the skill id returned as env variable `SKILLID`
4. Do your first deploy of your Serverless stack
5. Add the ARN of your lambda as env variable `ARNLAMBDA`
6. Run `sls alexa update` to deploy the skill manifest
7. Run `sls alexa build` to build the skill interaction model
8. Enable the skill in the Alexa app to start testing
