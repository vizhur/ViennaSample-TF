# For more details on configuring execution targets, go to: http://aka.ms/vienna-docs-exec

# Run tf_mnist.py in local conda environment.
# Please note this may not work on Windows. See bug https://msdata.visualstudio.com/Vienna/_workitems?id=44459&_a=edit&triage=true,
# But it does work on macOS.
az ml execute start -t local tf_mnist.py

# Run tf_mnist.py in a local Docker container.
az ml execute start -t docker tf_mnist.py

# Run tf_mnist.py in a Docker container in a remote machine.
# Note you need to create/configure myvm.compute.
az ml execute start -t myvm tf_mnist.py

