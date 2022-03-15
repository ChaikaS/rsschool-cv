# Sergei Chaikovsky

# My Contact Info
* #### E-mail: s.v.chaikovsky@gmail.com
* #### GitHub: [ChaikaS](https://github.com/ChaikaS "alt")
* #### LinkedIn: [sergei-chaikovsky](https://www.linkedin.com/in/sergei-chaikovsky-1ba08820b "alt")

# Summary
I am a highly motivated and capable engineer. My strengths are a high degree of self-organization, self-education, sociability, quickly assimilate new technologies and tools, solve non-trivial tasks, delve into the essence of the problem, focus on achieving results, high potential for working with a team.

# Skills
* JavaScript
* React
* Redux
* HTML
* CSS
* SASS
* Git\GitHub
* Jira
* Scrum

# Code examples

```
const testArray = [
  { id: 1, universe: "marvel", name: "Spider Man" },
  { id: 6, universe: "Walt Disney", name: "Avatar" },
  { id: 2, universe: "marvel", name: "Iron Man" },
  { id: 3, universe: "dc", name: "Aqua Man" },
  { id: 4, universe: "dc", name: "Bat Man" },
  { id: 5, universe: "Walt Disney", name: "X-mens" },
];
const groupBy = function (arr, key) {
  try {
    if (!Array.isArray(arr)) {
      throw new Error("Array is not provided");
    }
    if (!key) {
      throw new Error("Key is not provided");
    }
    return arr.reduce((acc, val) => {
      if (val[key] === undefined) {
        return {};
      }
      const property = val[key];
      if (property in acc) {
        return {
          ...acc,
          [property]: acc[property].concat(val),
        };
      }
      return { ...acc, [property]: [val] };
    }, {});
  } catch (error) {
    console.error(error);
  }
};
console.log(groupBy(testArray, "universe"));
```

# Education
* #### Belarusian State University of Transport
  + Master of construction and installation works
* #### RS.School
* #### Internal courses of Epam Systems
