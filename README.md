# profiler
Home Assistant Profiler

I've put together a profiler.

To install:

```
cd custom_components
git clone https://github.com/bdraco/profiler.git
```

Then setup the Profile integration (no restart needed).

Once its up an running call the `profiler.start` service.

<img width="530" alt="Screen Shot 2020-10-03 at 8 54 51 AM" src="https://user-images.githubusercontent.com/663432/94993366-24f08180-0556-11eb-98f6-7352b09a9183.png">

This will generate a `profile.TIMESTAMP.cprof` and `callgrind.out.TIMESTAMP` file in your home assistant directory after 60 seconds.

