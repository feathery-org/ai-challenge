# AI Backend Challenge

This project provides you with the foundation to extract data from a financial statement.

## Challenge

The goal of this challenge is to optimize the current extraction logic to improve the speed of the extraction. The current extraction completes in an average time of just over 30 seconds. While doing this, you should keep token usage in mind as we do not want to inflate it by a whole lot.

There are many ways to approach this challenge. We are looking to see how you navigate the challenge and showcase your problem solving skills.

Once you've completed the challenge, invite Andy (@ondrosh) and Peter (@bo-dun-1) as collaborators to your Github fork so we can review it. Please email us a link to the repository as well once you're finished!

## Requirements

1. Node v22.4.1 (`.nvmrc` included in project)
2. Yarn v1.22.x

## Getting Started

1. Fork the repository
2. Install the dependencies by running `yarn`
3. Copy the `.env.template` to a new file named `.env` in the root of the project. Copy your OpenAI API key into the new `.env` file.

You can run the extraction via the command:

```
yarn extract
```

## Notes

1. Do not modify the `src/index.ts` file.
2. The current extraction code can be found in `src/extraction.ts`.
3. The time and usage are logged each time you run `yarn extract`.
