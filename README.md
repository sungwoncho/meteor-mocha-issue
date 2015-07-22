➜  mocha-issue  meteor test-packages --velocity --driver-package velocity:console-reporter
[[[[[ Tests ]]]]]

=> Started proxy.
=> Started MongoDB.
=> Started your app.

=> App running at: http://localhost:3000/
W20150722-12:03:20.346(10)? (STDERR) error calling testsComplete function { [Error: Match error: Expected string, got undefined]
W20150722-12:03:20.347(10)? (STDERR)   message: 'Match error: Expected string, got undefined',
W20150722-12:03:20.347(10)? (STDERR)   path: '',
W20150722-12:03:20.347(10)? (STDERR)   sanitizedError:
W20150722-12:03:20.347(10)? (STDERR)    { [Error: Match failed [400]]
W20150722-12:03:20.348(10)? (STDERR)      error: 400,
W20150722-12:03:20.348(10)? (STDERR)      reason: 'Match failed',
W20150722-12:03:20.348(10)? (STDERR)      details: undefined,
W20150722-12:03:20.348(10)? (STDERR)      message: 'Match failed [400]',
W20150722-12:03:20.348(10)? (STDERR)      errorType: 'Meteor.Error' },
W20150722-12:03:20.348(10)? (STDERR)   errorType: 'Match.Error' }
PASSED mocha : true => is true
I20150722-12:03:20.489(10)? mocha: 1 tests passed (0ms)
TESTS RAN SUCCESSFULLY
