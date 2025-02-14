# Session Recap

## 🎯 **Session Overview**
In this session, we covered essential CSS techniques to enhance UI design and interactivity. Below is a recap of what we learned:

---

## 📌 **1. Transitions & Transforms**
### **Transitions**
- Used to create smooth animations between CSS property changes.
- Individual Properties:
  - `transition-property`: Specifies the property to be transitioned.
  - `transition-duration`: Sets how long the transition takes.
  - `transition-timing-function`: Defines the speed curve of the transition (easeinout usually).
  - `transition-delay`: Adds a delay before the transition starts.
- **Shorthand:**
  ```css
  .box {
      transition: transform 0.5s ease-in-out 0s;
  }
  ```

### **Transforms**
- Used to modify elements with effects like scaling, rotating, and skewing.
- Individual Properties:
  - `scale(x, y)`: Resizes the element.
  - `rotate(deg)`: Rotates the element.
  - `translate(x, y)`: Moves the element.
  - `skew(x, y)`: Skews the element.
- **Shorthand Example:**
  ```css
  .box {
      transform: rotate(15deg) scale(1.2) translate(10px, 5px);
  }
  ```

---

## 📌 **2. Pseudo-elements (::before & ::after)**
- Used to insert content before or after an element without modifying HTML.
- Individual Properties:
  - `content`: Defines the inserted content.
  - `position`: Positions the pseudo-element.
  - `background`: Adds background color or images.
- **Shorthand Example:**
  ```css
  .button::before {
      content: "🔥";
      position: absolute;
      left: 10px;
      background: transparent;
  }
  ```

---

## 📌 **3. !important & inherit**
### **!important**
- Forces a CSS rule to override all other rules.
- Example:
  ```css
  p {
      color: red !important;
  }
  ```

### **inherit**
- Forces a child element to take styles from its parent.
- Example:
  ```css
  .child {
      color: inherit;
  }
  ```

---

## 📌 **4. Keyframes & Animations**
- Used to create complex animations.
- Individual Properties:
  - `@keyframes`: Defines the animation steps.
  - `animation-name`: Specifies the keyframe name.
  - `animation-duration`: Determines how long the animation runs.
  - `animation-timing-function`: Controls the speed of the animation.
  - `animation-delay`: Delays the animation start.
  - `animation-iteration-count`: Specifies how many times the animation repeats.
  - `animation-direction`: Determines whether the animation runs forward, backward, or alternates.
- **Shorthand Example:**
  ```css
  @keyframes bounce {
      0% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0); }
  }
  .box {
      animation: bounce 2s ease-in-out infinite alternate;
  }
  ```

---

## 📌 **5. Text & Box Shadows**
### **Text Shadows**
- Adds shadow effects to text.
- Individual Properties:
  - `text-shadow: x-offset y-offset blur-radius color;`
- **Example:**
  ```css
  .text {
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
  }
  ```

### **Box Shadows**
- Adds shadow effects to elements.
- Individual Properties:
  - `box-shadow: x-offset y-offset blur-radius spread-radius color;`
- **Example:**
  ```css
  .box {
      box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
  }
  ```

---

## 📌 **6. Filter & Backdrop Filter**
### **Filter**
- Used to apply graphical effects like blur, brightness, contrast, and more.
- Individual Properties:
  - `blur(px)`: Applies a blur effect.
  - `brightness(%)`: Adjusts brightness.
  - `contrast(%)`: Adjusts contrast.
  - `grayscale(%)`: Converts the element to grayscale.
  - `hue-rotate(deg)`: Changes the hue of colors.
- **Example:**
  ```css
  .image {
      filter: blur(5px) brightness(120%) contrast(80%);
  }
  ```

### **Backdrop Filter**
- Search about the backdrop filter in css
  ```

---

## 🎯 **Final Assignment (6-Day Challenge)**
https://www.figma.com/design/FlT6WnfqYf9CcrZK5WtLXI/Ecommerce-Web-UI-Kit-(Community)?node-id=92-229&p=f&t=bvVAYI7i3Ot5CnFO-0
### **Create an Interactive Profile Card**
📌 **Requirements:**


