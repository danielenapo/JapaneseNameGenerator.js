# JapaneseNameGenerator.js
a random japanese name generator library for javascript

HOW TO USE:

first, create a new JapaneseNameGenerator object with the construnctor
```JapaneseNameGenerator([minimumNumberOfSyllables], [maximumNumberOfSyllables])```

(example)
```minSyllables=3;
maxSyllable=7;
nameGen= new JapaneseNameGenerator(minSyllable, maxSyllables);
```

to generate the name, use the method
```generateName()```
(example)
```
name=nameGen.generateName()
```

Here is an example of some of the names generated:
