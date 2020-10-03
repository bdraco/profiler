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

<img width="500" alt="Screen Shot 2020-10-02 at 11 34 29 AM" src="https://user-images.githubusercontent.com/663432/94947455-493f5600-04a3-11eb-8970-0f1ca9f53e5c.png">

This will generate a `profile.TIMESTAMP.cprof` and `callgrind.out.TIMESTAMP` file in your home assistant directory after 60 seconds.

I can use those files to get a better idea of what is going on

