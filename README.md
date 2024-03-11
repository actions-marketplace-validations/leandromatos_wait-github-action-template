# Wait - GitHub Action Template

A GitHub Action that waits for a given amount of time.

> [!IMPORTANT]
>
> This action is a template and should be used as a starting point for creating a new action. The action's name and description should be updated to reflect the new action's purpose, as well as the action's inputs, outputs, and example usage.

## Usage

### Inputs

The action accepts the following inputs:

| Name           | Description                         | Default |
|----------------|-------------------------------------|---------|
| `milliseconds` | The number of milliseconds to wait. | `2000`  |

### Outputs

The action provides the following outputs:

| Name   | Description       |
|--------|-------------------|
| `time` | The current time. |

### Example

The following is an example of how the action can be used:

```yaml
- name: Wait
  id: wait
  uses: actions/leandromatos/wait-github-action-template@v0.0.1-alpha.0
  with:
    milliseconds: 2000
```

In this example, the action waits for 2 seconds.

> [!NOTE]
> This repository contains a workflow that uses this action to validate its behavior. The workflow can be found in the `.github/workflows` directory.

## Contributing

Contributions are welcome. Please see the [CONTRIBUTING](CONTRIBUTING.md) file for more information.

## License

This package is under the MIT License. Please see the [LICENSE](LICENSE) file for more information.
