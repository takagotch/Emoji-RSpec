### Emoji-RSpec
---
https://github.com/cupakromer/emoji-rspec

```ruby
group :test do
  gem 'emoji-rspec'
end

RSpec.configure{ |c| c.fail_fast = true }

```

```
bundle
gem install emoji-rspec
.rspec
rspec --require emoji-rspec --format smiles

```

```
```
