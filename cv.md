# EUHENY ANDROSOV

### mr_zhenkins@mail.ru
### +375 29 155 07 91
### Minsk, Belarus

graduated from high school with a gold medal. during school time have been participate in olympiads(_inc. English_) and sport competitions.

Now a student of [BSUIR](bsuir.by) majoring in _systems engineer_. Thanks to university got apportunity to try myself in different fields of information technologys and now I am going to improve and develop personal skills in web development.

# Technologies

- HTML 5
- CSS 3
- SCSS(SASS) preprocessor
- JS



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
        