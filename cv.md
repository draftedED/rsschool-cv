# Pavel Pavlov

## Future frontend developer

***********

## Contact information

* __Location:__ Voronezh, Russia
* __Phone:__ +7 951 147 48 72
* __Email:__ pavel.pavlov.edc@gmail.com
* __GitHub:__ [draftedED](https://github.com/draftedED)

***********

## About me

I'm 30 years old. I worked as a Cloud Engineer for the last 5 years. And I've decided to try myself in Frontend.

***********

## Skills

* __HTML__
* __CSS__
* __SCSS__
* __JavaScript__
* __Git\Github__
* __VS code, IntelliJ IDEA__

***********

## Code example

```
export const apiRequest = async (filter) => {
  const apiAccessKey = "###dpmiGSK0UdXWz-GILj7nLkVs5swHXv7RygE57###";
  const apiURL = `https://api.unsplash.com/search/photos?client_id=${apiAccessKey}&page=1&per_page=30&query=${filter}`;

  try {
    const apiResponse = await fetch(apiURL);
    const apiData = await apiResponse.json();

    if (apiResponse.status === 200 && apiResponse.ok) {
      apiResult = apiData.results;
      setPhotos();
    }
  } catch (error) {
    console.log(error);
  }
};
```

***********

## Education

* __Voronezh State University__
    * Faculty of Computer Science

***********

## Courses

* __RS Schools Frontend Course Stage 0__ ([RS School](https://rs.school/))
* __HTML Academy__ ([HTMLAcademy](https://htmlacademy.ru/))
* __HTML + CSS + Javascript on CodeBasics__ ([CodeBasics](https://code-basics.com/ru))

***********

## Languages

* __Russian__ - Native
* __English__ - Intermediate