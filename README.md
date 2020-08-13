# Builders Checkpoint

Please read the instructions below carefully.

### Getting Started:

#### Option 1 - testem is globally installed

- If you have been running `testem` by running the `testem` command in your terminal, you are ready to go. Run `testem` to run the test specs. If you receive any errors or you don't have `testem` globally installed, refer to option 2.

```sh
  $ cd ${name-of-the-checkpoint-repository}
  $ testem
  TEST'EM 'SCRIPTS!
  Open the URL below in a browser to connect.
  http://localhost:7357/
```

<hr>

#### Option 2 - Install Testem Locally

If you don't have `testem` installed globally on your machine, complete the following steps:

1. Run the command:

```sh
$ npm install
```

Note: the command **needs to be executed inside of the checkpoint directory**.

2. After the installation is complete, when you want to run `testem` run the command:

```sh
npm run test
```

3. Here are all of the steps:

```sh
$ cd ${name-of-the-checkpoint-repository}
$ npm install
$ npm run test
TEST'EM 'SCRIPTS!
Open the URL below in a browser to connect.
http://localhost:7357/
```

### Rules

This checkpoint is similar to the Bulders Test First exercises — reverse engineer each spec, and write code to pass it. **Do not alter** any of the TestSpecs unless instructed to do so; **_all solutions should be written in the empty `.js` files in each folder_**.

### Scoring

This checkpoint is scored out of **28 points**. In each suite, the later specs are usually more challenging / valuable. The suites are weighted as follows:

- 00-autocomplete - 4.00 Points
- 01-mine-finder - 5.00 Points
- 02-keypad-entry - 5.00 Points
- 03-word-score - 6.00 Points
- 04-sort - 8.00 Points

### Tips

- Each folder has a README.md file; **read the README files** to get an overview of each Test Spec and Point Value, as well as problem concept.
- You are encouraged to `git commit` at regular milestones.

---

## Submitting

When time is complete or when you finish the code, perform the following:

1. Commit all your changes with `git commit -am "submission for deadline"`.

- **Also**: `git push` your commits back up to your own personal fork on Github.

Good luck!
