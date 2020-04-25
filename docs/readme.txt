1、编译命令
Windows版
服务端x86：GOOS=windows GOARCH=386 make release-server
客户端x86：GOOS=windows GOARCH=386 make release-client
服务端x64：GOOS=windows GOARCH=amd64 make release-server
客户端x64：GOOS=windows GOARCH=amd64 make release-client

Linux版
服务端x86：GOOS=linux GOARCH=386 make release-server
客户端x86：GOOS=linux GOARCH=386 make release-client
服务端x64：GOOS=linux GOARCH=amd64 make release-server
客户端x64：GOOS=linux GOARCH=amd64 make release-client

MacOS版
服务端x86：GOOS=darwin GOARCH=386 make release-server
客户端x86：GOOS=darwin GOARCH=386 make release-client
服务端x64：GOOS=darwin GOARCH=amd64 make release-server
客户端x64：GOOS=darwin GOARCH=amd64 make release-client