![image](https://img.shields.io/badge/Vue%20js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![image](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![image](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![image](https://img.shields.io/badge/-Scss-eee?style=for-the-badge&logo=sass)
## CodePen Demo

### `Responsive Web Design (RWD) Support `
[![CodePen](https://img.shields.io/badge/CodePen-View-000000?style=for-the-badge&logo=codepen)](https://codepen.io/justin880929/pen/Yzowegd)




## Props Type
```
interface propsObj={
  isOpen:Ref<boolean>;
  isDarkMode:Ref<boolean>;
  routesSetting: [
    {
      link: string;
      name: string;
      tooltip: string;
      icon: string
    }
  ];
}
```
### Props Example
```
const propsObj={
  isOpen: ref(false),
  isDarkMode:ref(false),
  routesSetting: [
    {
      link: '/home',
      name: 'Home',
      tooltip: 'Home',
      icon: 'bx-home-alt',
    }
  ]
}
```
### UI Default Setting
```
const propsObj={
  isOpen: ref(false),
  isDarkMode:ref(false),
  routesSetting: [
    {
      link: '/home',
      name: 'Home',
      tooltip: 'Home',
      icon: 'bx-home-alt',
    },
    {
      link: '/purchase',
      name: 'Purchase',
      tooltip: 'Purchase',
      icon: 'bx-cart-alt',
    },
    {
      link: '/user',
      name: 'User',
      tooltip: 'User',
      icon: 'bx-user',
    },
  ]
}
```
## Icon
[![Boxicons](https://img.shields.io/badge/Icon%20Library-Boxicons-c4caef?style=for-the-badge&logo=boxicons&logoColor=white)](https://boxicons.com/)
