#Global Process Methods Learning

| Syntax | Description |
|--------|-------------|
| process.pid | Will return the id of the process running in the port |
| process.argv| is an Array, first element in the array is node, the second will be the JS filename, and the remaining elements will be additional CLI args|
| process.env| is an object containing the user environment.|
| process.platform | returns the current pltform the app is running one.g: darwin, linux etc.|
| process.release | Returns an object containing metadata describing the current release of node, same as node --version except more detailed.|
| process.versions | A compiled-in property that returns the node version|
| process.stdin() | is a writable string to standard in|
| process.stdout() | a writable stream to standard out|
| process.uptime() | returns the number of seconds that node has been running |
| process.memoryUsage() | returns an object that contains data about the memory usage of the the node process in bytes. |
| process.exit([code]) | Ends the process with a specified code, if ommitted exit uses success code 0 |
| process.kill(pid[, signal]) | sends a signal to the process, signal is the string describing the signal to send, signal names are strings. |


