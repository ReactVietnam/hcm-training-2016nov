# React Traning
Mỗi lesson tương ứng với khoảng thời gian 2 ngày (5 tiếng).
Khóa học hướng tới việc xây dựng các ứng dụng thực tế, mỗi phần đều có assignment để người học nghiên cứu.


## Lesson 1: Building app basic with React (thời gian 5 tiếng)
__*Mục đích*:__ Cung cấp các kiến thức cơ bản về React, JSX, babel
* Write react components -  viết react component
* Render data to page - render component trên trang web
* Make component communicate - xây dựng component
* Handle user events - Xử lý các sự kiện
* Capture user input - Bắt các sự kiện input
* Remote servers &  react lifecycle methods - Xử lý dữ liệu tương tác với server

*Project:* Xây dựng ứng dụng quản lý sản phẩm cơ bản với React

---

#### Slide 1.1 - Get started with react Component (30 phút)
- What's react ? Why react ? Who's use react ? React ecosystem.
- Requirement learn react. (Các kỹ năng để học React)
- What we'll learn in lession 1 (Những điều chúng ta sẽ học trong lession 1)
- Component-based Architecture (Cấu trúc ứng dụng react)
- What is a React Component (Thế nào là react component)
- The virtual DOM Explained (Giải thích cơ bản về Virtual DOM)
- The virtual DOM in Action
- NPM introduction
- Webpack introduction
- Setup editor
- Creating our first project react with create-react-app cli
- Project React structure by create react app
- Writing our first Component
- Rendering Our First React Component
- Application react structure (api, components, ..)
- Summary in slide

---

#### Slide 1.2 - Understanding JSX (30 phút)
- Difference naming React Component  & HTML native elements
- A new Way to Write Javascript (JSX)
- Getting used to the jsx Syntax
- From JSX to HTML
- Using the Date Object in JSX
- Iterating Arrays in JSX
- Summary in slide

#### Slide 1.3 - React Props (30 phút)
- Introduction the app we're building
- Shopping app application Architecture
- HTML Markup application
- Writing the **Product** Component
- Writing the **ProductLists** Component
- React Components Accept Arguments
- Reading Props in the **Product** Component
- Passing and Receiving Arguments Review
- Summary in slide

#### Slide 1.4 - Props - Passing Dynamic Arguments (30 phút)
- Problem: Props aren't dynamic yet
- Javascript Object Array
- Mapping an Array to JSX
- Passing Dynamic Props
- Using unique Keys on List of Components
- Using custom method **getProductLists** in class Component
- Bonus custom new method for product lists: *getTotalProducts(), getTotalProductsSoldOut*
- Summary

#### Slide 1.4 - Component state (30 phút)
- Show and hide products list
- Different ways to Manipulate the DOM
- Direct DOM Manipulation
- Indirect DOM Manipulation
- How to use State in a Component
- How to update a Component State
- Causing state change
- Handling Click Events
- Summary

#### Slide 1.5 - Array, Object in ES6 (30 phút)
- Array: map, filler, merge, reduce
- Object: splice object, merge object, update key in object

#### Slide 1.5 - Synthetic Events (30 phút )
- Add new ProductForm
- Adding an Event Listener to form
- Problem: Can't access user input in handleSubmit();
- Accessing Form Data from Hanlder  - Refs
- Data about products live when add from ProductForm
- Adding functionality to add new Product
- Rendering component from state

#### Slide 1.6 - Remote server - fetch data (30 phút)
- Loading products from remote server
- Adding axios to fetch data
- How to fetch data in component
- Setting state with data from remote server
- React Lifecycle Methods
- Fetching Data on the mouting pharse
- Auto update product list (like realtime, use setInterval auto fetch)
- Memory leaks on page change with setInterval
- Preventing memory leaks with componentWillUnmount clearInterval
- Summary

#### Slide 1.7 - Remote server - adding and deleting remote server (30 phút)
- Delete product from API
- Passing a Callback Prop To Component
- Adding event listener to show confirm
- Add product from API
- One-way Control Flow
- Summary

#### Actions: Assignments (90 phút)
- Building a search photos by 500px API
- Building show projects github user

----

## Lesson 2:  Understand more in react, and use React Router (thời gian 5 tiếng)

**Mục đích** Cung câp các kiến thức:
- Hiểu chi tiết về ES6, các function, class
- Cài đặt các gói hỗ trợ biên dịch như SASS, LESS, .. 
- Hiểu về webpack, cài đặt livehot loading để tiết kiệm thời gian viết ứng dụng
- Thuần thục các kỹ năng về component trong react hiểu các khái niệm định nghĩa trong react
- Xây dựng trang SPA, di chuyển qua lại giữa các trang với react router

#### Slide 2.1 Understanding ES6 (40 phút)
- Let, const
- arrow function
- composing function
- class Object
- Project: 
	- Build ShoppingCart Class caculator total product

#### Slide 2.2 Understanding Webpack (50 phút)
- Install new sass loader, other loader
- Install new preset ES2017, decorators
- Install package reactstrap - apply style bootstrap
- Live hot loading
- Project:
	- Build form register validation

#### Slide 2.3 Understand more in react (90 phút)
- Stateless Functional Components in React
- PropTypes
- Nested component props children
- **this* keyword
- Highorder Components
- ES6 promise
- Project: 
	- Load github, and change display project (grid, show thumbnails)
	- Build app todo lists
	- Build feeds  and comment on feed

#### Slide 2.4 React router (180 phút)
- Introduction react router
- Nested props children react router
- Get params from react router
- Project
	- Build application shopping:
		- Display products lists
		- Display products by search
		- Display products by category
		- View product
		- Add product to cart
		- View cart

#### Assignment
- Build newleter page like medium, have comments

---

## Lesson 3: Work and work (5 tiếng)
**Mục đích**:  Rèn luyện, quen với việc sử dụng các react component, xây dựng các component mang tính reusable

- Build movies application (like hdonline.vn) (120 phút)
	- Search film
	- Show films
	- Preview trailer
	- Comment on film
- Build read story application + Firebase (like watpad)	(120 phút)
	- Show stories
	- Show information story
	- Read chapter detail
- Server rendering (60 phút)

#### Assignment
- React component testing
- React drag and drop sortable

---

##  Lesson 4: Test in react, Redux introduction (5 tiếng)

#### Slide 1.1 Introduction for drag and drop (react dnd) (20 phút)
- DragSourceable
- DragConnect

#### Slide 1.2 Test component with jest (30 phút)

#### Slide 1.3 Redux introduction (30 phút)
- Problem with large react for manager state
- Flux architecture (compare with MVC)
- Single state
- Store
- Reducers
- Actions
- Examples in jsbin

#### Slide 1.4 Ussage with react (90 phút)
- Simple app todo lists with redux
- Convert app movies to redux

#### Slide 1.5 (150 phút)
- Build app login + firebase with redux
- Build app Paypal 
	- withdraw, deposit
	- History withdaw, history deposit
	- Require login
	- Send money

#### Assignments
- Convert Read story to redux app


## Lesson 5 - 6 : Work real project (10 giờ)
**Mục đích** : Xây dựng ứng dụng thương mại điện tử  với các tính năng
- Trang hiển thị cho người dùng
	- Trang đăng ký, đăng nhập cho thành viên
	- Hiển thị danh sách các sản phẩm
	- Xem sản phẩm
	- Voting, comment cho sản phẩm
	- Thêm sản phẩm vào giỏ hàng
	- Trang checkout sản phẩm
	- Quản lý tình trạng các đơn hàng (pending, chờ xử lý, ..)
- Trang admin dashboard
	- Quản lý danh sách sản phẩm, thêm, sửa xóa sản phẩm
	- Tìm nhanh sản phẩm trong dashboard
	- Quản lý đơn hàng, tìm kiếm nhanh đơn hàng, lọc đơn hàng theo theo các trạng thái đơn hàng, chuyển trạng thái các đơn hàng
	- Quản lý thành viên, thêm sửa xóa, cấp quyền cho thành viên
	- Cài đặt các thông tin cơ bản
- Server rendering cho SEO

Tổng kết bài học với React.