# EUHENY ANDROSOV

### mr_zhenkins@mail.ru
### +375 29 155 07 91
### Minsk, Belarus

# Common info

I graduated from high school with a gold medal. While at schol I participated in various olympiads, including *English*. Besides I took an active part in sport competitions.

Now I'm a student of [BSUIR](bsuir.by) majoring in _systems engineer_. Due to university I have a wide range of opportunities to try myself in different areas of information technology and now I have an urge to improve personal skills in _web development_.

# Technologies

- HTML 5
- CSS 3
- SCSS(SASS) preprocessor
- JS

# Sample code

```
const moreElems = document.querySelectorAll('.more');
console.log(moreElems);

const modalElem = document.querySelector('.modal');

const openModal = () => {
    modalElem.classList.remove('hidden');
};

const closeModal = () => {
    modalElem.classList.add('hidden');
};

moreElems.forEach((moreElem) => {
    moreElem.addEventListener('click', openModal)
    modalElem.addEventListener('click', (event) => {
        const target = event.target;

        if (target.classList.contains('overlay') || target.classList.contains('modal__close')) closeModal();
    })
})
```
* # Education

    - General secondary education, incomplete higher education.

* # Level of english

    - Intermediate