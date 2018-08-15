[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/incubator-password-strength.svg)](https://vaadin.com/directory/component/incubator-password-strength)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/incubator-password-strength.svg)](https://vaadin.com/directory/component/incubator-password-strength)

# &lt;incubator-password-strength&gt;

[&lt;incubator-password-strength&gt;](https://vaadin.com/components/incubator-password-strength) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-password-strength/master/screenshot.png" width="200" alt="Screenshot of incubator-password-strength">](https://vaadin.com/components/incubator-password-strength)

## Example Usage

```html
  <incubator-password-strength header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-password-strength>
```
