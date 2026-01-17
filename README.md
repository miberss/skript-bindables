# skript-bindables
A bindables library for Skript inspired by [kotlin-bindables](https://github.com/LukynkaCZE/kotlin-bindables) system.

## What are bindables?
A Bindable is a struct that can hold a value and provide callbacks to when the value is changed.

## Dependencies
- oopsk-1.0-beta2
- Skript-2.14.x
- skript-reflect-2.6.2

## Usage
More here will be filled out later, but for now you can look at the `examples/` folder to see concrete usages with header descriptions.

## Extras
You can use `bind_update(bindable, value?)` to run the callbacks and update the value to them without explicitly changing the field.

You can also use `bind_set_silently(bindable, value)` which will set the value of the bindable without running any of the callbacks

## Contributing
Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests on the [GitHub repository](https://github.com/miberss/skript-bindables#).

## License
skript-bindables is open-source and available under the [NON-AI-UNLICENSE](https://raw.githubusercontent.com/non-ai-licenses/non-ai-licenses/main/NON-AI-UNLICENSE)