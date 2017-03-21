# Linux-Tips

#show directory space usage (-s: summarize; -h: human readable)
du -hs * | sort -h


#want set temporary working directory in .sh (don't forgot the popd in the end):
pushd SOME_PATH
run_stuff
...
...
popd




