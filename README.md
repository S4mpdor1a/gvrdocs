# GVR Docs
Dokumentasi api gvr ygy
Cek file [axeron.js](https://github.com/S4mpdor1a/gvrdocs/axeron.js), lebih lengkap (walau banyak comment block :v)

# Axeron Instances
class
## Exec
Execute shell command
```javascript
Axeron.exec(commands, option = {});
// example:
Axeron.exec('echo hi');
```

## Toast
Nampilin notifikasi kayak roti
```javascript
Axeron.toast(titleOrMessage, messageOrDuration, duration);
// example:
Axeron.toast('apa hah', 10);
```
## OptimizeApp
Optimalkan aplikasi
```javascript
Axeron.optimizeApp(packageName = null);
// example:
Axeron.optimizeApp('com.dts.freefireth');
```

# StormDownload
class
## Download
Download sesuatu dari url
```javascript
download(url, path);
// example:
download('https://pomf2.lain.la/f/i6c1h78o.jpg', '/sdcard/hello.jpg');
```
