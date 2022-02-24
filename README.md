# learn-typescript-with-phero

back again with #Programming_Hero to learn typescript

## ***difference between js and ts***
- `ts` is a ***superset*** of `js`
- TSC (**Transcript compiler**) keeps compling the codes while you are writting the codes. On the other hand, in `js` you have to write the codes and then you got to run them and see the errors in the `console`. But in `TS` you will get the errors while you are writting the codes with the help of **TSC**.
- To understand  this first follow the example;
    ```
    let person ={
        name: "md. amanullah parvez",
        occupation: "student"
    }
    ```
    in `JS` if you find `person.nationality` you will get `undefined` as output which can lead you to `error` in the next step if you try find `person.natinality.id`. But `TS` will give you error on the first step so it will be easier for you to find the bugs in your codes.


    ## Install and run TS
    you can install Typescript in two ways;
    |install globally|install as developer dependancy|
    |----------------|-------------------------------|
    |by installing it globally you can access it from anywhere and when someone is cloning your repo and installing `npm` they will also get the dependencies.|Only accessible withing the project you are working on.|
    |npm install -g typescript|npm install typescript --save-dev
    yarn add typescript --dev|


    ## To run dependency and dev dependency
    - to run dev dependencies you need to run `npx ...` eg. `npx tsc -v`