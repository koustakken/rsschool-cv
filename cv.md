# **[rsschool-cv](https://koustakken.github.io/rsschool-cv/)**

# **Tema Ivanov**

# **Contacts**

- **Location**: Yekaterinburg, Russia
- **E-mail**: kous.takken@gmail.com
- **GitHub**: [koustakken](https://github.com/koustakken)

# **Summary**

Enthusiast, learning and developing. In search of something new and beautiful

# **Code examples**

```js
export const getScore = (gameStamps: Stamp[], offset: number): Score => {
  let current = gameStamps.find((value) => value.offset === offset);

  while (!current) {
    offset -= 1;
    current = gameStamps.find((value) => value.offset === offset);
  }
  const { home, away } = current.score;

  return {
    home,
    away,
  };
};
```

# **Education**

- College: Kurgan College of Technology

# **Languages**

- Russian: Native
- English: A1/A2
