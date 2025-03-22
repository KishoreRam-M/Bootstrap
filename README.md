## **🚀 Bootstrap Mastery Roadmap (Beginner to Advanced)**
Mastering Bootstrap involves learning its core concepts, utilities, components, and customization techniques. Follow this **structured roadmap** to go from **beginner** to **advanced** in Bootstrap.

---

## **🔰 Phase 1: Beginner Level (1-2 Weeks)**
🎯 **Goal:** Understand Bootstrap basics, grid system, and components.

### ✅ **Step 1: Setup & Installation**
- Visit [Bootstrap official site](https://getbootstrap.com/)
- Use Bootstrap via:
  - **CDN** (Easiest)
  - **Download & Link Locally**
  - **Install via npm** (`npm install bootstrap`)

### ✅ **Step 2: Bootstrap Grid System (Core Concept)**
- **Learn the Grid System** (`.container`, `.row`, `.col`)
- **Breakpoints & Responsive Design** (`col-sm-`, `col-md-`, `col-lg-`, etc.)
- **Nesting Columns**
- **Column Offsets & Ordering**

📝 **Practice:**  
```html
<div class="container">
  <div class="row">
    <div class="col-md-6 bg-primary text-white">Column 1</div>
    <div class="col-md-6 bg-secondary text-white">Column 2</div>
  </div>
</div>
```

### ✅ **Step 3: Typography & Utilities**
- **Typography Classes** (`.text-primary`, `.fs-3`, `.fw-bold`)
- **Spacing Utilities** (`.m-3`, `.p-4`)
- **Borders & Shadows** (`.border`, `.shadow-lg`)
- **Background & Color Utilities** (`.bg-light`, `.text-danger`)

📝 **Practice:**  
```html
<p class="text-success fs-4 fw-bold">Bootstrap is awesome!</p>
```

---

## **🔰 Phase 2: Intermediate Level (2-3 Weeks)**
🎯 **Goal:** Learn Bootstrap components, forms, modals, and navigation.

### ✅ **Step 4: Bootstrap Components**
- **Buttons** (`.btn`, `.btn-primary`, `.btn-lg`)
- **Cards** (`.card`, `.card-body`)
- **Alerts** (`.alert`, `.alert-warning`)
- **Badges & Pills** (`.badge`, `.rounded-pill`)

📝 **Practice:**
```html
<button class="btn btn-primary">Click Me</button>
```

### ✅ **Step 5: Forms & Inputs**
- **Form Controls** (`.form-control`, `.form-select`)
- **Input Groups** (`.input-group`)
- **Validation States** (`.is-invalid`, `.is-valid`)

📝 **Practice:**
```html
<input type="text" class="form-control" placeholder="Enter name">
```

### ✅ **Step 6: Navigation & Modals**
- **Navbar** (`.navbar`, `.nav-item`, `.dropdown`)
- **Modals** (`.modal`, `.modal-dialog`)

📝 **Practice:**
```html
<button class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">Open Modal</button>
```

---

## **🔰 Phase 3: Advanced Level (3-4 Weeks)**
🎯 **Goal:** Customize Bootstrap, build real-world projects.

### ✅ **Step 7: Advanced Components**
- **Carousels** (`.carousel`)
- **Tooltips & Popovers** (`.tooltip`, `.popover`)
- **Progress Bars** (`.progress`)

### ✅ **Step 8: Bootstrap Customization**
- **Override Bootstrap variables using SCSS**
- **Custom themes (`_variables.scss`)**
- **Modify grid breakpoints & colors**

### ✅ **Step 9: Real-World Project**
💡 **Project Idea:**  
🔹 Build a **Landing Page** using Bootstrap  
🔹 Include Navbar, Hero Section, Cards, Testimonials  
🔹 Use Grid System & Utility Classes  

📝 **Example Structure:**
```html
<div class="container">
  <h1 class="text-center text-primary">Welcome to My Portfolio</h1>
  <div class="row">
    <div class="col-md-4">
      <div class="card">
        <div class="card-body">
          <h5 class="card-title">Project 1</h5>
          <p class="card-text">A cool Bootstrap project</p>
        </div>
      </div>
    </div>
  </div>
</div>
```

---

## **🎯 Final Step: Mastering Bootstrap with JavaScript**
- Learn **Bootstrap JavaScript components** (`Collapse`, `Carousel`, `Modal`)
- Use **Bootstrap with jQuery** and **React**
- Explore **Bootstrap Themes** like AdminLTE, MDBootstrap

---
