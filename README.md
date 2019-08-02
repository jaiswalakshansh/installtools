# InstallTools
Here i will list all the steps in installing and setting different tools in linux based machines
# GO

## [TOMNOMNOM httprobe was so cool i was in love with this one but this tool was made in go somehow i was not able to find any good tutorial idk why but atlast solved the small problem of environment setting )

* STEPS
* 1)GO TO https://golang.org/dl/ and install one for linux and save it in DOWNLOADS
* 2)cd Downloads
* 3)tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz #this extract in usr/local
* 4)now come to main directory by typing cd
* 5)fire these 
*   mkdir go
*    cd /go
*    mkdir bin src pkg
* 5)Set environment
* pico ~/.bashrc and write there below export lines and save
* export GOPATH=~/go
* export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin
* Now u are all set to install try tomnomnom one's its just epic man..
