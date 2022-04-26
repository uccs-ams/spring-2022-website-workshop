# Spring 2022 UCCS AMS Website Workshop
Contains Hugo binaries and project structure for Spring 2022 UCCS AMS Workshop.

## Getting Started
Clone this repository from GitHub via:

```bash
git clone https://github.com/uccs-ams/spring-2022-website-workshop.git
```

Navigate to the new `spring-2022-website-workshop` directory created by cloning
this repository, and check out the branch corresponding to your operating system:

Windows (x86-64):
```
git checkout windows
```

MacOS (x86_64):
```
git checkout macos
```

MacOS (ARM64):
```
git checkout macos-arm64
```

Linux (x86-64):
```
git checkout linux
```

Once you've checked out the appropriate branch, you can start your `hugo` server
by running:

```
./hugo -D serve
```

Open http://localhost:1313/ in your browser to see your website! It'll be blank
at first until we add some content.
