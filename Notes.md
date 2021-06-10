# Notes and links of good information
- VA | Platform [Documentation](https://depo-platform-documentation.scrollhelp.site/index.html) ([Old Link](https://department-of-veterans-affairs.github.io/va.gov-team/))
- [va.gov-team](https://github.com/department-of-veterans-affairs/va.gov-team)
    - [Accessibility page](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/platform/accessibility) (has broken links)
    - [Best Practices](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/platform/accessibility/508-accessibility-best-practices.md) (has broken links)
    - Correct Link to [Chrome Colorblinding plugin](https://chrome.google.com/webstore/detail/colorblindly/floniaahmccleoclneebhhmnjgdfijgg?hl=en)
- [WCAG (Web Content Accessibility Guidelines) Quick Ref](https://www.w3.org/WAI/WCAG21/quickref/)
- [deque Resources](https://dequeuniversity.com/resources/)

## Plugins
- [WAVE Chrome Extension at the Google Web Store](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
- [deque axe](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)

- [Web AIM Contrast Checker](https://webaim.org/resources/contrastchecker/)

One of my favorite and most used debugging snippet: 
if you're fighting with focus management, copy-and-pasting this into your console will print out the currently focused element and will do so on every focus change 
(programmatic or user driver). It's a simple thing but I find it so helpful when I'm stuck in the weeds on a thing.

```
document.addEventListener('focusin', function() {
  console.log('focused: ', document.activeElement)
}, true);
```
