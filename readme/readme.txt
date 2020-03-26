Linter for CudaLint plugin.
Supports Go lexer.
It uses gometalinter from https://github.com/alecthomas/gometalinter

1) Install Go
2) To allow "gometalinter" to run, you must add Go to system PATH.
For example, how to do this on Linux:
https://www.linode.com/docs/development/go/install-go-on-ubuntu/
3) Install "gometalinter" like this

    go get github.com/alecthomas/gometalinter
    gometalinter --install --update

Ported from SublimeLinter-contrib-gometalinter by Medvosa
