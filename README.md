# treetracker-testing
Pressure test, test tool, test report and test code.

# How to run the test locally
1. Install Maestro
Run the following command to install Maestro on macOS, Linux or Windows (WSL):
```
curl -fsSL "https://get.maestro.mobile.dev" | bash
```
If you're on macOS, you can use Homebrew instead of the install script above:
```
brew tap mobile-dev-inc/tap
brew install maestro
```
Note: Follow the information after installing Maestro, you may need to export some environments

2. Create and launch Android/iOS Emulator or USB-connected physical device.
Note: At the moment, Maestro does not support physical iOS devices

3. Build and install Android/ios TreeTracker app.

4. Run the test.
```
maestro test ${PATH_TO_TEST_FILE}
```

More instruction: [Maestro Offical Website](https://maestro.mobile.dev/)
