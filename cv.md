# Frontend React developer

## Devis Dumler

- _e-mail: devisdumler@gmail.com_

* _github: https://github.com/devisd_

### About me:

##### _I started learning frontend more than two years ago on my own. Completed courses at GOIT as a Full-Stack developer. I continue to study this area on my own and in a team with the same students, as well as with working Frontend specialists._

##### _At the moment, I managed to work in team projects on layout and vanilla JS._

##### _Gained invaluable experience figuring out someone else's code. I have experience with the Git/GitHub version control system._

##### _I tried myself in the role of Team-Lead in team projects._

##### _I continue to study Full-Stack: React, Redux, Node.js, Express, etc._

### Tech Skills:

- HTML
- CSS / SASS
- JavaScript
- React.js
- Redux / Redux Toolkit
- BEM
- Figma

### Soft Skills:

- Scrum
- Agile
- GTD
- Teamwork

### Code exsample:

```
import { useSelector, useDispatch } from 'react-redux';
import { filter } from 'redux/store';

const Filter = () => {
  const dispatch = useDispatch();
  const filterItems = useSelector(state => state.filter);

  const handleChange = event => {
    dispatch(filter(event.currentTarget.value));
  };

  return (
    <div>
      <label>
        Find contacts by name
        <input
          type="text"
          name="filter"
          value={filterItems}
          onChange={handleChange}
        />
      </label>
    </div>

export default Filter;
```

### Work experience:

Single projects

- [Portfolio](https://github.com/devisd/goit-markup-hw-08)
- [Movies](https://github.com/devisd/05-movies)
- [Phonebook (redux)](https://github.com/devisd/asyncThunk-phonebook)

Team projects

- [IceCream](https://github.com/devisd/positiveteam)
- [MovieMania](https://github.com/devisd/MovieMania)

### Education:

- GOIT - Fullstack developer course
- GLO-Academy - HTML/CSS intensive
- GLO-Academy - JavaScript intensive

### English language: Pre-Intermediate
