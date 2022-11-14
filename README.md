# Material for Elk workshop at ADC22, Mon. 14th 2022
Directory layout:

```
.
├── binaries    # binaries for macOS and Linux
├── elkpy       # elkpy library and examples, for controlling sushi over gprc through python 
├── elkcpp      # elkcpp library and examples, for controlling sushi over grpc through C++
└── config      # sushi configuration files
```

elkpy and elkcpp are submodules, which in turn depend on additional submodules.
So, do clone with '--recurse-submodules', or, run 'git submodule update --init --recursive' once you've cloned this repository.
