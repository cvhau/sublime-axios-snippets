Axios Snippets For Sublime Text
==========================================

This is a collection of [axios](https://github.com/axios/axios) API snippets for [Sublime Text](http://www.sublimetext.com)

Installation
------------

Use Sublime Text's [Package Control](http://wbond.net/sublime_packages/package_control) (Preferences -> Package Control -> Install Package -> Axios Snippets) to install this package.

Snippets
--------
* __axios__
  ```javascript
  axios({
    method: 'get',
    url: '',
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.request | axiosr__
  ```javascript
  axios.request({
    method: 'get',
    url: '',
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.get | axiosge__
  ```javascript
  axios.get('url', {
    params: {
      key: 'value',
    },
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.delete | axiosde__
  ```javascript
  axios.delete('url').then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.head | axioshe__
  ```javascript
  axios.head('url').then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.options | axiosop__
  ```javascript
  axios.options('url').then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.post | axiospo__
  ```javascript
  axios.post('url', {
    key: 'value',
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.put | axiospu__
  ```javascript
  axios.put('url', {
    key: 'value',
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.patch | axiospa__
  ```javascript
  axios.patch('url', {
    key: 'value',
  }).then((response) => {
    // TODO
  }).catch((error) => {
    console.error(error);
  }).finally(() => {
    // TODO
  });
  ```

* __axios.create | axioscr__
  ```javascript
  axios.create({
    baseURL: 'base-url',
    timeout: 5000,
    headers: {
      'X-Requested-With': 'XMLHttpRequest',
    }
  });
  ```

&nbsp;

#####Also support some Promise commands

* __promise new | Promise new.__
  ```javascript
  new Promise((resolve, reject) => {
    // TODO
  });
  ```

* __promise | Promise__
  ```javascript
  Promise((resolve, reject) => {
    // TODO
  });
  ```

Contributions
---------------------
If you have any ideas and new features, please fork and create a pull request to [repository](https://github.com/cvhau/sublime-axios-snippets).
