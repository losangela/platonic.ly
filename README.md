# Platonicly

### Usage

```
git clone https://github.com/hrla29-just-friends-mvp/friends-mvp.git
cd friends-mvp

git checkout -b your_github_handle
yarn install
yarn run db:generate
```

#### To run the app in Expo:
```
yarn start
```

#### In case you need to reset database
```
yarn run db:regenerate
```

#### If you want to run xcode simulator

yarn add expo-cli
expo client:install:ios

after simulator is opened, click on the top right plus and get the url from Metro Bundler

#### Before pull request && to update to current develop commit on your local:
Before your start, make sure your current branch is up-to-date. Then run the following commands:

```
git checkout develop
git pull origin develop
git checkout your_github_handle
git rebase develop
git pull origin your_github_handle
```
The last line of code will update/fix the HEAD of your_github_handle

### Contributors:

- Angela Choi https://github.com/losangela
- Jeff Cho https://github.com/jeffcho0227
- Li Sun https://github.com/lsun1
- Morgan Lin https://github.com/morganl92
