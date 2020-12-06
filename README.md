# Instruction
## How to test
run  ` helm dependency update .` in the app1 helm directory, you should get the message saying chart is updated
then run `helm install <release> . -f values.yaml --dry-run` in app1 helm to see objects got created
