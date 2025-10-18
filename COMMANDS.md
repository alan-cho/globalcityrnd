# Quick Command Reference

This project uses **Rake** (Ruby's task runner) for common commands, similar to npm scripts.

## Available Commands

| Command          | Description                                            |
| ---------------- | ------------------------------------------------------ |
| `rake start`     | Start development server on port 4000                  |
| `rake dev`       | Start server with live reload (browser auto-refreshes) |
| `rake start3000` | Start server on port 3000                              |
| `rake build`     | Build site for production deployment                   |
| `rake clean`     | Clean generated files                                  |
| `rake install`   | Install dependencies                                   |
| `rake`           | Default task (runs `start`)                            |

## Quick Start

```bash
# First time setup
rake install

# Start development server
rake dev

# Visit http://localhost:4000 in your browser
```

## Comparison to npm

| npm             | Rake                               |
| --------------- | ---------------------------------- |
| `npm start`     | `rake start`                       |
| `npm run dev`   | `rake dev`                         |
| `npm run build` | `rake build`                       |
| `npm install`   | `rake install` or `bundle install` |

## Adding New Tasks

Edit the `Rakefile` to add custom tasks. Example:

```ruby
desc "Description of your task"
task :taskname do
  sh "your command here"
end
```

## See All Tasks

```bash
rake -T
```
