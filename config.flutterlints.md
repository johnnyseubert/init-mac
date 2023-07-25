```yaml
include: package:flutter_lints/flutter.yaml

analyzer:
   exclude:
      - '**/*.g.dart'
      - 'lib/generated/**'

linter:
   rules:
      avoid_unused_constructor_parameters: true
      avoid_redundant_argument_values: true
      avoid_unnecessary_containers: true
      unnecessary_await_in_return: true
      always_declare_return_types: true
      sort_child_properties_last: false
      prefer_single_quotes: true
      prefer_final_locals: true
      avoid_empty_else: true
      empty_catches: true
      avoid_print: true
      use_build_context_synchronously: false
```
