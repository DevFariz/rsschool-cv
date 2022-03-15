# Fariz Ramazanov

## Contact Information

* **E-mail:** farizramazanov38@mail.ru
* **Phone:** +994505552159
* **Address:** Baku, Azerbaijan
* **Github:** [devFariz](https://github.com/DevFariz)

## Brief information about myself

I'm a self-educated web developer. I'm very interested in coding and I can spend whole day just coding. I want to learn new technolgies in frontend and improve my skills here. I have finished the stage#0 of this course and got certificated. Today I have completed nearly 10 projects in front-end (test projects).

## Skills

* HTML5
* CSS3/SASS
* Javascript
* Jquery
* Git, Github
* C# (basic)
* Figma (for web developers)
* BEM(Block Element Modifier)

## Code Example

Your function takes two arguments:

* current father's age (years)
* current age of his son (years)

Сalculate how many years ago the father was twice as old as his son (or in how many years he will be twice as old).

```
function twiceAsOld(dadYearsOld, sonYearsOld) {
  
  let n = 0;
  if(dadYearsOld/sonYearsOld > 2)
    {
      while(dadYearsOld !== 2 * sonYearsOld)
        {
          dadYearsOld++;
          sonYearsOld++;
          n++;
        }
      return n;
    }
  else if(dadYearsOld/sonYearsOld === 2)
    {
      return 0;
    }
  else
    {
      while(dadYearsOld !== 2 * sonYearsOld)
        {
          dadYearsOld--;
          sonYearsOld--;
          n++;
        }
      return n;
    }
  
}
```