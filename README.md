# AppSheet / Google Apps Script / Data Studio Training 2026

> การพลิกโฉมการทำงานในคณะเศรษฐศาสตร์ด้วย AppSheet, Google Apps Script และ Data Studio: การออกแบบ พัฒนา และประยุกต์ใช้งานเพื่อเพิ่มประสิทธิภาพองค์กร


# Resources
- [Information](/src/info.pdf)
- [Diagram](https://link.excalidraw.com/l/9PltHIQHZMD/97g3a97dWzd)

# Demo
- [Form](https://script.google.com/macros/s/AKfycbzAqVp_fHHfoG-_ps0zWaBpFitKqM2_tybKaqqNeFtKsiRZAn8JhCuYCCI2OuyDWy9pzQ/exec)
- [Dashboard](https://datastudio.google.com/s/mmiReemdReE)

# AppSheet
- Current time
```
NOW()
```
- Data Validity
```
[end_time] > [start_time]
```
- Virtual column formula
```
CONCATENATE([room], " - " , [name], " - ", [purpose])
```

# AppScript

- [Code to send email notification](https://gist.github.com/nnnpooh/09f577c7fd44ea2f633d978e8f0846c7#file-appscript_email-js)