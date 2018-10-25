# Ruby example
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

# Shell example
```sh
#!/bin/ksh

for item in 1 2 3 4 
do
  echo "I am item ${i}"
done

while read line
do
  echo bob
done < /etc/fstab

bob()
{
	echo "This is some stuff"
	echo "Doing it here"
}

bob
```

