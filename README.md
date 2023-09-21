# Writing Good Documentation

## Step 1 - Using codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share code**. 
A good __Cloud engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

In order to create codeblocks in markdown, you need three backticks (`)
Not to be confused with quotation.
```
# Define the Person class
class Person
  attr_accessor :name

  def initialize(name)
    @name = name
  end

  def greet
    "Hello, #{@name}! Nice to meet you."
  end
end

# Create an instance of the Person class
john = Person.new("John")

# Print out a greeting
puts john.greet  # Output: Hello, John! Nice to meet you.

```
- When you can you should attempt to apply syntax highlighting to your codeblocks.

```ruby
# Define the Person class
class Person
  attr_accessor :name

  def initialize(name)
    @name = name
  end

  def greet
    "Hello, #{@name}! Nice to meet you."
  end
end

# Create an instance of the Person class
john = Person.new("John")

# Print out a greeting
puts john.greet  # Output: Hello, John! Nice to meet you.

```

![del](https://github.com/SerVErThread/github-docs-example/assets/24904136/dfab5c3c-ae18-4e63-a1a6-51e1f0bcd31f)

- Make note of where that learning never ends.
- It is a constant challenge to develop yourself and strive for excellence.
- You are the master of your destiny.

<img width="200px" src="https://github.com/SerVErThread/github-docs-example/assets/24904136/dfab5c3c-ae18-4e63-a1a6-51e1f0bcd31f" />

Good cloud engineers use code blocks for both Code and Errors that appear in the console.
Here is an example of y=using a codeblock that appweras in bash.

```bash
RuntimeError: Division by zero error!
        from (irb):2:in `divide'
        from (irb):5
        from /usr/bin/irb:11:in `<main>'
```
> Here is an example of y=using a codeblock that appears in bash.

## Step 2 - How to take screenshots

A screenshot is when you capture part of your screen from your laptop, desktop or phone.

This is not to be confused with a photo with your phone.

**DON'T DO THIS**


## Step 3 - Use Github Flavoured Task Lists

Github extends Markdown to have a list where you can check off items.  [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- |  --- |
| Cloud | `:cloud:`| :cloud:|
| Alarm Clock | `:alarm_clock:`| :alarm_clock:|
| Cloud with Loghtning | `	:cloud_with_lightning:`|	:cloud_with_lightning:|

## Step 5 - How to create a table.

You can use the following markdown format to create tables.

```md
| Name | Shortcode | Emoji |
| --- | --- |  --- |
| Cloud | `:cloud:`| :cloud:|
| Alarm Clock | `:alarm_clock:`| :alarm_clock:|
| Cloud with Loghtning | `	:cloud_with_lightning:`|	:cloud_with_lightning:|
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

[Secret Window Hidden Garden](secret-window/hidden-garden.md)

## External References

- [My Repo](https://github.com/SerVErThread/github-docs-example/edit/main/README.md)
- [GFM Getting started](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>[1]</sup>
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables with extension](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
