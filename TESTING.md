# TESTING

## Manual Testing

---

| Feature | Action | Expected Result | Tested | Passed | Comments |
| --- | --- | --- | --- | --- | --- |

| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the home page | Yes | Yes | - |
| Blog | Click on the "Blog" link | The user is redirected to the blog page | Yes | Yes | - |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| YouTube icon | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Facebook icon | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Twitter icon | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |
| Instagram icon | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |

| Home page | | | | | |
| Blog Posts | Hover over a blog post | The background image opacity is set to 1.00 | Yes | Yes | - |

<!-- Keep going from hereererere!!!!!! -->
| Blog page | | | | | | 
| Blog Posts in Featured Section | Hover over a blog post | The background image opacity is set to 1.00 | Yes | Yes | - |
| Image in the gallery | User hover the image | Pet's name and description appear on the image | Yes | Yes | - |
| "Contact Us" button in Call to action section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |

| Gallery page | | | | | |
| "Contact Us" button in Hero section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Image in the gallery | User hover the image | Pet's name and description appear on the image | Yes | Yes | - |
| "Contact Us" button in Call to action section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |

| Contact page | | | | | |
| First name input | Enter the first name | The first name is entered | Yes | Yes | If user doesn't enter the first name, the error message appears |
| Last name input | Enter the last name | The last name is entered | Yes | Yes | If user doesn't enter the last name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Adopt and donate checkbox | Click on the checkbox | The checkbox is checked | Yes | Yes | These checkboxes are not required as the user can choose not to adopt or donate and other reasons for contacting |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |

| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |

## Bugs

---

* Hamburger menu does not work in Firefox browser - Firefox does not currently support the CSS :has() pseudo-class, although steps are being taken to amend this: [link](https://developer.mozilla.org/en-US/docs/Web/CSS/:has)
