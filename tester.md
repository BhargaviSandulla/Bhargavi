{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "Basic tfsec",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example"]
    },
    {
      "name": "Basic doc gen",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec-docs/"
    },
    {
      "name": "custom_functions test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/custom_functions"]
    },
    {
      "name": "foreach test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/foreach"]
    },
    {
      "name": "foreach module test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/foreach-module/src"]
    },
    {
      "name": "config override test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/with_config_overrides"]
    },
    {
      "name": "module loading without init test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/971/configurations/project"]
    },
    {
      "name": "workspace test",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": [
        "${workspaceFolder}/example/workspace",
        "--workspace",
        "somethingelse"
      ]
    },
    {
      "name": "tfsec s3 module",
      "type": "go",
      "request": "launch",
      "mode": "auto",
      "program": "${workspaceFolder}/cmd/tfsec/main.go",
      "args": ["${workspaceFolder}/example/1010"]
    }
  ]
}