# Coding Exercise: CSS

We would like for you to build out the HTML and CSS for the following navbar. We would like to navbar to be responsive, and you may choose your own breakpoint. Feel free to use CSS, SCSS, SASS, LESS, or whatever else suits your fancy, but no CSS libraries or frameworks — we want to see your own raw CSS code.

We are looking for clean, elegant, and easy to understand code.

Bonus points for SEO and Accessibility considerations. Feel free to include a README if you wish to explain anything in words, or better yet, add those as code comments in your submission.

### Design Mockups and Assets

**Full/Desktop Mockup** (screenshot not true size)

![desktop navbar](img/desktop_navbar.png)

**Mobile Mockup** (screenshot not true size)

![mobile navbar](img/mobile_navbar.png)

**Chartmetric logo**

```xml
<svg id="cm-logo-icon" data-name="cm-logo-icon" width="27" height="27" viewBox="0 0 27 27" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M18.29 6.14V5.14C18.29 4.87478 18.1846 4.62043 17.9971 4.43289C17.8096 4.24536 17.5552 4.14 17.29 4.14C17.0248 4.14 16.7704 4.24536 16.5829 4.43289C16.3954 4.62043 16.29 4.87478 16.29 5.14V6.71C16.29 6.97522 16.1846 7.22957 15.9971 7.41711C15.8096 7.60464 15.5552 7.71 15.29 7.71C15.0248 7.71 14.7704 7.60464 14.5829 7.41711C14.3954 7.22957 14.29 6.97522 14.29 6.71V1C14.29 0.734784 14.1846 0.48043 13.9971 0.292893C13.8096 0.105357 13.5552 0 13.29 0C13.0248 0 12.7704 0.105357 12.5829 0.292893C12.3954 0.48043 12.29 0.734784 12.29 1V17.28C12.29 17.5452 12.1846 17.7996 11.9971 17.9871C11.8096 18.1746 11.5552 18.28 11.29 18.28C11.0248 18.28 10.7704 18.1746 10.5829 17.9871C10.3954 17.7996 10.29 17.5452 10.29 17.28V5.1C10.29 4.83478 10.1846 4.58043 9.99711 4.39289C9.80957 4.20536 9.55522 4.1 9.29 4.1C9.02478 4.1 8.77043 4.20536 8.58289 4.39289C8.39536 4.58043 8.29 4.83478 8.29 5.1V10.28C8.29 10.5452 8.18464 10.7996 7.99711 10.9871C7.80957 11.1746 7.55522 11.28 7.29 11.28C7.02478 11.28 6.77043 11.1746 6.58289 10.9871C6.39536 10.7996 6.29 10.5452 6.29 10.28V9.12C6.29 8.85478 6.18464 8.60043 5.99711 8.41289C5.80957 8.22536 5.55522 8.12 5.29 8.12C5.02478 8.12 4.77043 8.22536 4.58289 8.41289C4.39536 8.60043 4.29 8.85478 4.29 9.12V17.41C4.29 17.6752 4.39536 17.9296 4.58289 18.1171C4.77043 18.3046 5.02478 18.41 5.29 18.41C5.55522 18.41 5.80957 18.3046 5.99711 18.1171C6.18464 17.9296 6.29 17.6752 6.29 17.41V13.85C6.29 13.5848 6.39536 13.3304 6.58289 13.1429C6.77043 12.9554 7.02478 12.85 7.29 12.85C7.55522 12.85 7.80957 12.9554 7.99711 13.1429C8.18464 13.3304 8.29 13.5848 8.29 13.85V21.52C8.29 21.7852 8.39536 22.0396 8.58289 22.2271C8.77043 22.4146 9.02478 22.52 9.29 22.52C9.55522 22.52 9.80957 22.4146 9.99711 22.2271C10.1846 22.0396 10.29 21.7852 10.29 21.52V20.84C10.29 20.5748 10.3954 20.3204 10.5829 20.1329C10.7704 19.9454 11.0248 19.84 11.29 19.84C11.5552 19.84 11.8096 19.9454 11.9971 20.1329C12.1846 20.3204 12.29 20.5748 12.29 20.84V25.62C12.29 25.8852 12.3954 26.1396 12.5829 26.3271C12.7704 26.5146 13.0248 26.62 13.29 26.62C13.5552 26.62 13.8096 26.5146 13.9971 26.3271C14.1846 26.1396 14.29 25.8852 14.29 25.62V10.28C14.29 10.0148 14.3954 9.76043 14.5829 9.57289C14.7704 9.38536 15.0248 9.28 15.29 9.28C15.5552 9.28 15.8096 9.38536 15.9971 9.57289C16.1846 9.76043 16.29 10.0148 16.29 10.28V21.46C16.29 21.7252 16.3954 21.9796 16.5829 22.1671C16.7704 22.3546 17.0248 22.46 17.29 22.46C17.5552 22.46 17.8096 22.3546 17.9971 22.1671C18.1846 21.9796 18.29 21.7252 18.29 21.46V17.03C18.29 16.7648 18.3954 16.5104 18.5829 16.3229C18.7704 16.1354 19.0248 16.03 19.29 16.03C19.5552 16.03 19.8096 16.1354 19.9971 16.3229C20.1846 16.5104 20.29 16.7648 20.29 17.03V17.66C20.3467 17.88 20.4766 18.0742 20.6584 18.2105C20.8401 18.3468 21.0629 18.4172 21.29 18.41C21.5552 18.41 21.8096 18.3046 21.9971 18.1171C22.1846 17.9296 22.29 17.6752 22.29 17.41V9.15C22.29 8.88478 22.1846 8.63043 21.9971 8.44289C21.8096 8.25536 21.5552 8.15 21.29 8.15C21.0248 8.15 20.7704 8.25536 20.5829 8.44289C20.3954 8.63043 20.29 8.88478 20.29 9.15V13.45C20.29 13.7152 20.1846 13.9696 19.9971 14.1571C19.8096 14.3446 19.5552 14.45 19.29 14.45C19.0248 14.45 18.7704 14.3446 18.5829 14.1571C18.3954 13.9696 18.29 13.7152 18.29 13.45V6.14ZM2 13.14V13.39C2 13.6552 1.89464 13.9096 1.70711 14.0971C1.51957 14.2846 1.26522 14.39 1 14.39C0.734784 14.39 0.48043 14.2846 0.292893 14.0971C0.105357 13.9096 0 13.6552 0 13.39V13.14C0 12.8748 0.105357 12.6204 0.292893 12.4329C0.48043 12.2454 0.734784 12.14 1 12.14C1.26522 12.14 1.51957 12.2454 1.70711 12.4329C1.89464 12.6204 2 12.8748 2 13.14ZM26.39 13.14V13.38C26.39 13.6452 26.2846 13.8996 26.0971 14.0871C25.9096 14.2746 25.6552 14.38 25.39 14.38C25.1248 14.38 24.8704 14.2746 24.6829 14.0871C24.4954 13.8996 24.39 13.6452 24.39 13.38V13.14C24.39 12.8748 24.4954 12.6204 24.6829 12.4329C24.8704 12.2454 25.1248 12.14 25.39 12.14C25.523 12.14 25.6547 12.1665 25.7774 12.218C25.9 12.2695 26.0111 12.3449 26.1043 12.4399C26.1974 12.5349 26.2706 12.6475 26.3197 12.7712C26.3688 12.8948 26.3927 13.027 26.39 13.16V13.14Z" fill="url(#paint0_linear_1723_12897)"/><defs><linearGradient id="paint0_linear_1723_12897" x1="6.29624" y1="6.4021" x2="20.0495" y2="20.1553" gradientUnits="userSpaceOnUse"><stop stop-color="#00DD74"/><stop offset="1" stop-color="#0BA0E0"/></linearGradient></defs></svg>
```

You should be able to save this to a file and call it `CM_logo-icon.svg`

### Requirements

- **Deliverables:** HTML markup with corresponding CSS code to render a Chartmetric navbar
- Navbar should be fluid and span 100% width in all cases (desktop + mobile — meaning your solution should be responsive)
- Height of navbar is 50px (ignore screenshot sizing above)

### Specs

- Ignore the gray padding in the screenshots above, as the navbar (dark blue bg) is intended to be flush to the top, left, and right
- Non-logo icons are from FontAwesome 5. If you are unable to use the free version or get FontAwesome working, feel free to use another font icon library, and it’s ok if the icons are not exactly the same (we are interested in your coding ability and not so much exactly matching the icons)
- Background color for the navbar is `#1d2b38`

## Additional Notes

- Preferably, no CSS frameworks or libraries, as we like seeing _your own_ raw code (however, we have seen great submissions utilizing an external framework/library, so if you do choose to go this route make it count)
- Bonus points for building this as React component/components — but if you do choose to go this route, we’ll be looking for _good, proper_ use of React (we’ve seen many solutions in React that really made no sense to have been done in React)

## How to Submit

- Easiest way is to upload to a Github repo, and share the url with us
- Alternatively, you may zip all necessary files together and email it to us
