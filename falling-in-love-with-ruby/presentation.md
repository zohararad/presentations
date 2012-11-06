= data-x="0" data-y="0"

# Falling in love with Ruby
## Zohar Arad. September 2012
<img src="http://aux4.iconpedia.net/uploads/863724227.png" class="right">

---
= data-x="1500" data-y="-1500"

## Modern programming languages
### Star Wars version

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/stormtroopers.jpg">
  <figcaption>
    <p>.NET Graduation Ceremony</p>
    <p class="src">source: http://deathstarpr.blogspot.co.il/</p>
  </figcaption>
</figure>

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/c3po.jpg">
  <figcaption>
    <p>PHP Hackathon</p>
    <p class="src">source: http://www.starwars.com</p>
  </figcaption>
</figure>

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/yoda-dooku.jpg">
  <figcaption>
    <p>Python developer, kicking a Java developer's ass</p>
    <p class="src">source: http://starwars.wikia.com</p>
  </figcaption>
</figure>

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/jarjarbinks.jpg">
  <figcaption>
    <p>Perl Developers Meetup</p>
    <p class="src">source: http://starwars.wikia.com</p>
  </figcaption>
</figure>

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/ewoks.jpg">
  <figcaption>
    <p>Javascript Developers Debugging IE8</p>
    <p class="src">source: http://www.starwars.com/</p>
  </figcaption>
</figure>

---
= data-x="3000" data-y="0"
<figure>
  <img src="images/jedi-class.jpg">
  <figcaption>
    <p>Ruby Master Class</p>
    <p class="src">source: http://www.starwars.com/</p>
  </figcaption>
</figure>

---
= data-x="1500" data-y="0"
## Developer Happiness
### Coding should be fun

---
= data-x="3000" data-y="0"
**Ruby code is** readable, consistent, concise

---
= data-x="4500" data-y="0"

## Ruby

```ruby
name = "Natalie Portman"
puts "Luke's mom rocks!" unless name.blank?
```

## PHP
```php
$name = "Natalie Portman";
if(strlen($name) > 0){
  echo "Luke's mom rocks";
}
```

---
= data-x="6000" data-y="0"
```ruby
10.times do
  puts "Hi"
end

@credit += 1 if @coins > 2
start_game! unless waiting?

x = 0
until x > 10 do
  x += 1
end

file_content = File.open('somefile.txt','r'){ |f| f.read }
```

---
= data-x="0" data-y="-1500" data-rotate-z="60"

## Mixins and Modules
### Because multiple-inheritence sucks

---
= data-x="1500" data-y="-1500" data-rotate-z="0"

**Mixins** are a cleaner way to reuse code

---
= data-x="3000" data-y="-1500" data-rotate-z="0"

Functionality is **self-contained** in modules and **mixed** into objects

---
= data-x="4500" data-y="-1500" data-rotate-z="0"

Code is **cleaner** and more **organized**.

No inheritence chain to worry about

---
= data-x="6000" data-y="-1500" data-rotate-z="0"

```ruby
module Logger
  def log(msg)
    puts msg
  end
end

class Car
  include Logger
  def drive
    log "Driving"
  end
end
```

---
= data-x="0" data-y="-3000" data-rotate-z="60"
## Rubygems
### Ruby code collaboration eco-system

---
= data-x="1500" data-y="-3000" data-rotate-z="0"

Rubygems is the **driving force** of the Ruby

eco-system success

---
= data-x="3000" data-y="-3000" data-rotate-z="0"

No more **missing** packages, **conflicting** versions and **broken** dependencies

---
= data-x="4500" data-y="-3000" data-rotate-z="0"

Clear standards and tools for **authoring** and **distribution**

<br/>

**Versioning**, **dependencies** and **load paths** are handled during install

---
= data-x="6000" data-y="-3000" data-rotate-z="0"

Bundle management with Bundler makes development and deployment a breeze

---
= data-x="7500" data-y="-3000" data-rotate-z="0"

```ruby
source 'https://rubygems.org'

gem 'mongoid', '~>3.0'
gem 'rspec', :group => :test
```

---
= data-x="7500" data-y="-3000" data-rotate-z="0"

```xml
&lt;modelVersion&gt;4.0.0&lt;/modelVersion&gt;
&lt;groupId&gt;org.sonatype.mavenbook.simple&lt;/groupId&gt;
&lt;artifactId&gt;simple&lt;/artifactId&gt;
&lt;packaging&gt;jar&lt;/packaging&gt;
&lt;version&gt;1.0-SNAPSHOT&lt;/version&gt;
&lt;name&gt;simple&lt;/name&gt;
&lt;url&gt;http://maven.apache.org&lt;/url&gt;
&lt;dependencies&gt;
    &lt;dependency&gt;
        &lt;groupId&gt;junit&lt;/groupId&gt;
        &lt;artifactId&gt;junit&lt;/artifactId&gt;
        &lt;version&gt;3.8.1&lt;/version&gt;
        &lt;scope&gt;test&lt;/scope&gt;
    &lt;/dependency&gt;
&lt;/dependencies&gt;
```

---
= data-x="0" data-y="0" data-rotate-z="60"
## Testing as a culture
### Reliability on the bleeding edge

---
= data-x="1500" data-y="0" data-rotate-z="0"

## Excellent testing frameworks

* RSpec
* Test::Unit
* Cucumber
* Capybara

---
= data-x="3000" data-y="0" data-rotate-z="0"

Public code is **always** tested - Early adpotion is usually safe

<br>

**Collaboration** is easier - Responsibilities are clear

---
= data-x="4500" data-y="0" data-rotate-z="0"

```ruby
describe MyController do
  before :each do
    get '/some_url'
  end

  it "should have a response body" do
    last_response.body.should_not be_blank
  end
end
```

---
= data-x="0" data-y="-1500" data-rotate-z="60"
## Faster development cycles
### It's all about developer performance

---
= data-x="1500" data-y="-1500" data-rotate-z="0"

Convention over configuration

(so long Java XML files)

---
= data-x="3000" data-y="-1500" data-rotate-z="0"

Focus on programming rather than making trivial decisions

---
= data-x="4500" data-y="-1500" data-rotate-z="0"

The **right tools** for the job (and they're tested)

<br>

Variaty is good. Not too much variaty is better!

---
= data-x="0" data-y="-3000" data-rotate-z="60"
## Ruby made me a better programmer

---
= data-x="1500" data-y="-3000" data-rotate-z="0"

Coding style and conventions are clear and easy to pick up

---
= data-x="3000" data-y="-3000" data-rotate-z="0"

Community tools and standards help me focus on the problem rather than menial tasks

<br/>

For example - **Rake**, **RVM**, **Bundler**

---
= data-x="4500" data-y="-3000" data-rotate-z="0"

Ruby doesn't get upset when I don't implement an interface or declare types (Java, .NET)

<figure class="noframe">
  <img width="250" src="http://www.freshrant.com/wp-content/uploads/2010/06/grumpy-dwarf.jpg" />
  <figcaption>
    <p class="src">From http://www.freshrant.com</p>
  </figcaption>
</figure>

---
= data-x="4500" data-y="-3000" data-rotate-z="0"

Ruby doesn't get upset when I don't want to get my hands dirty (Python)

<figure class="noframe">
  <img height="250" src="http://www.redwindsoftware.com/blog/image.axd?picture=/dug.png" />
  <figcaption>
    <p class="src">From http://www.redwindsoftware.com</p>
  </figcaption>
</figure>

---
= data-x="4500" data-y="-3000" data-rotate-z="0"

Ruby doesn't get upset when I forget to configure php.ini just right (PHP)

<figure class="noframe">
  <img height="250" src="http://1.bp.blogspot.com/-wciNCtuDOps/TuGfSccI9VI/AAAAAAABtqk/A0Drj8QEhh0/s1600/Brainy+Smurf.jpg" />
  <figcaption>
    <p class="src">From http://kooztop5.blogspot.co.il/</p>
  </figcaption>
</figure>

---
= data-x="6000" data-y="-3000" data-rotate-z="0"

Ruby doesn't get in the way of my code so I can do things **faster**, more **reliably** and with **less headaches**

---
= data-x="0" data-y="-3000" data-rotate-y="120"

# Thank You!
## Questions?