# Link
[Website Link](https://cirvianum-daw.github.io/mp9-pj-uf2-optimitzacio-imatges-gsingh704/src/)



# Images

## Explanation

|        |        |         |                                                                                                                                                                     |
| ------ | ------ | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image  | Format | Size    | Justification                                                                                                                                                       |
| logo   | svg    | 6.5kg   | svg is a vector image format, so it is very small in size and can be scaled to any size without losing quality. My logo is a simple logo, so I can use svg format.  |
| Dishes | webP   | various | webp is a new image format that is smaller than jpg and png. It is supported by most browsers. It greatly reduces size while preserving a great deal of quality.    |

But I just used parcels auto conversion to optimize my images

## Sharp and Parce

[Video Link](https://drive.google.com/file/d/1pjKJtN406Z4S55O7WjKnMNHboIkfE0xS/view?usp=sharing)

## Manually Converting

I have used imagemagick , which is used by many GUI programs. It is a command line tool. Which can be used to automate the converting process

Command used by me is

    magick convert in.jpg -quality 80 -define webp:method=6 out.webp

|         |                                                                                                                                                                                                  |                                                                                                                                                                                                  |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|         | Original                                                                                                                                                                                         | New                                                                                                                                                                                              |
| Image   | ![](https://lh7-us.googleusercontent.com/eRQF7DduSOuroNYdg9ZI7A4PNrBsdqw7D0ISwIOqV30U6FD4BBbS9QladlidJvFomBMj6A98nvj0MeLmo1pu7iMoSZ-ppWXj4IUyI81QYYeiBKjQ1ZYf_YxvYfoDYj0Jj2_xBIKEuRWxfKYW1UeQSw) | ![](https://lh7-us.googleusercontent.com/nW_H3RF4KEVxTBNII7QMEsdFGxe_bVHefKj6GO7cSNJhv-hWNVxQXsXnXlaq2NPhvsE2wkCKANdwkv29w-0HvWZ7yb4xQtWtr_4tMpROVRpiYvsDWZPemB8fiDWKprgoZsol4k6OmOXmNBXfwUtPNw) |
| Size    | 224 Kb                                                                                                                                                                                           | 113.4 kb                                                                                                                                                                                         |
| Quality | 100%                                                                                                                                                                                             | 80%                                                                                                                                                                                              |
| Saving  |                                                                                                                                                                                                  | 49 %                                                                                                                                                                                             |
| Zoom in | ![](https://lh7-us.googleusercontent.com/Rz1WNGn4YvqTi2gJlhsZwt7qcnSj8qjvm3GHBEW74zJwVkaraso1x_srFGKPcgHPeV9JvFdTTPYCwL3A5txkoZcqB21Dvtzc7BcidJ6Trk6tslJHlSw_EhBqsap5TOJ1UIQgclocFzjVGGZsewe7Rg) | ![](https://lh7-us.googleusercontent.com/oq5WSY5KKtsro26msjSf0JshpvSMdB0kgAu--h0MDUAz1_S7mLIqg-p72JiQzZKCfaTiFq8N6a_NQWyKwXIAEXwc2IMDmgskZvSpuHxyizk3r10jubGlVDdOCPaKj1EQa-ydzYE7QVoWyGmAu_VbGw) |

|         |                                                                                                                                                                                                  |                                                                                                                                                                                                  |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|         | Original                                                                                                                                                                                         | New                                                                                                                                                                                              |
| Image   | ![](https://lh7-us.googleusercontent.com/JJCezHwrBbeEvsA-zPvZcoN6itz4DXWG_U4lCoaVc4wGqIzaCY7eNIkpJfhGGGTOllLZYenjJxlO-oHeF6IQentOjr-8UbN_gYLKFzs-G7dt_wnDLLxYPeUVJeNGTlow2J8FUSTu2kJRDTQbq9c_WA) | ![](https://lh7-us.googleusercontent.com/tdWca34fav8o_NqEXgfdRqs5ZvmjBY-yXxrKpaBx7n_Eqfp_4b6eV2EIeCgV-3uo7NC-Ey6T-Fq5tqtUSAhBmmpTtAYJMjp_DJDa6adP30oL8pvAy5Z2Dd2Egj0t567D-DvPlzQo-_SzVyBkHwTH7w) |
| Size    | 2.2MB                                                                                                                                                                                            | 108 kb                                                                                                                                                                                           |
| Quality | 100%                                                                                                                                                                                             | 80%                                                                                                                                                                                              |
| Saving  |                                                                                                                                                                                                  | 95%                                                                                                                                                                                              |

# CSS</a>

##  CSS Animation</a>

```css

     <a href="./dishes.html"
        class="inline-flex items-center justify-center px-5 py-3 border-2 border-indigo-600 rounded-lg hover:bg-indigo-600 hover:text-white text-indigo-600 font-semibold">
        See all dishes
        <span class="ml-3 text-xl animate-ping inline-flex rounded-full h-6 w-6 bg-indigo-600 items-center justify-center text-white">
            &rarr;
        </span>
    </a>

```

WIth `animate-ping`, creating animations with Tailwind are very easy. There are four kinds of animation in Tailwind.

- Basic usage

- Spin

- Ping

- Pulse

- Bounce

![](https://lh7-us.googleusercontent.com/jUKVxT7VQOXzJrFng5B1ESN2Nl3DIf2r3VZooG-gLWPfKZr8z6_qO2p6NRhS53HY1Hj4BseUgKOxYAXqm8dcfFNb9uD4Cy8PyVy-pqcWk7Au332tefFcQvVlunEk8KSPqSvLNLlMKtqfm2qxGtBOtQ)

## CSS Clip Path

The clip-path CSS property creates a clipping region that sets what part of an element should be shown. It's a very good way to retouch images and create cool designs on images. I have Created an image that is larger on one side and on other smaller, matching text div height

|                                                                                                                                                                                                  |                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![](https://lh7-us.googleusercontent.com/li-6LsscRJ-PxNEmNQNgt-0RKpmrjDYyl_09an89YGDv7s81ya61Tsw9OVron8lYnP0dTI5BZI9wbbK7Er0R3vhxDpeJxeViWIm1QOMHUhTVXc7qg5NndOKcpfFLpDMeg8ggtf2u9WEW2um29PWE2Q) | ![](https://lh7-us.googleusercontent.com/9PaLSOFwf298z-x8vnLevGEvkPiPpRW3fd4BhCBtCCGBdC76ULjvEQFNa_Kci7o2FAlG4qPTgqsqh7Y_M84yIW7SDU-T3alh5iD9XhxNbFU4uJu2RFIV3oGuVRz5MImQ_5WGfwkt1D87lMMGwUGT6A) |

```css
.clip-path {
   clip-path: polygon(0% 0, 100% 10%, 100% 90%, 0 100%);
}
```

## SVG Animation 

In About Page I have put rotating animation to my log that is an svg

```css
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
.logo-animation {
  animation: rotate 5s infinite linear;
}
```

![](https://lh7-us.googleusercontent.com/sgsOvqxch_s6RKxmAvmt0zFeZRFoK_U3iOWr6FaCDFkA9U5FfDmxZ9hlqERdV0DRdOSX22tnLvx1nAbm1oXpHfUChTS7Co5bcQlJxJzC_JFIZx67qcyGjFeIhMMenwqIjZDKnt0datwh7KOSaB4y2Q)
