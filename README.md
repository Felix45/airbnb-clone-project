# AirBnB Clone Project! 🏠✨
Airbnb Clone is a full-stack web application that mimics the core functionality of Airbnb: users can browse, filter, and book short-term rental listings; hosts can create and manage their own listings; and both parties can review past stays.

## Tech Stack
- Front-End
   - React with TypeScript, Next.js for server-side rendering and static site generation, TailwindCSS for styling.
- Back-End
    - Python, Django, and MySQL
-  Other tools
   - Redux or Context API for state management, REST for API integration, Jest for testing.


## UI/UX Design Planning
A user-friendly booking interface streamlines the reservation process by minimizing form fields and guiding users with clear calls-to-action while building trust through transparent pricing and security. To achieve this I intend to implement the following key features.

The key features implemented in this project include the following
- Property Listing View
     - This is the main interface of the AirBnB clone. It shows a clean and modern layout with various property listings displayed, each with a title, price, and a brief description. The design focuses on user-friendly navigation and visual appeal.

- Listing Detailed View
    - This page illustrates a detailed view of a specific property listing within the AirBnB clone. It highlights key features such as the property’s name, location, price, and additional details like amenities. The interface emphasizes clarity and ease of use for potential renters.

- Simple Checkout View
    - This page showcases the booking or reservation process for the selected property in the AirBnB clone. It may include options for selecting dates, the number of guests, and finalizing the booking. The design is streamlined to ensure a smooth user experience.

- Search Functionality
    - A robust search feature enabling users to find properties based on criteria like location, price, and availability.

Identifying a mock-up’s design properties—such as its layout grid, typography choices, color palette, and interactive elements—is essential for ensuring visual consistency, maintaining brand integrity, and guiding developers and stakeholders in translating a static concept into a functional product

### Fonts
  - Quicksand (500, 600)
  - Source Sans Pro (500, 600)

### Colors
- #34967C, - #161117, - #FFFFFF, - #FAC02B, - #131212, - #CACACA|

 
## Project Roles and Responsibilities
- Project Manager
  - The Project Manager is the leader of the project and is responsible for planning, executing, and closing projects.
- Frontend Developers
  - Frontend developers focus on the client-side of the application, ensuring a smooth and engaging user experience
- Backend Developers
  - Backend developers work on the server-side of the application, managing data and ensuring seamless communication between the server and the frontend.
- Designers
  - Designers are responsible for the visual and interactive aspects of the application, ensuring it is user-friendly and aesthetically pleasing.

- QA/Testers
  - QA/Testers ensure the quality and reliability of the application by identifying and fixing bugs before release.

- DevOps Engineers 
  - DevOps Engineers focus on the deployment and operational aspects of the software, ensuring smooth and efficient delivery
- Product Owner
  - The Product Owner is responsible for defining the vision of the product and ensuring it meets user needs.

- Scrum Master
  - The Scrum Master facilitates Agile processes and helps the team follow Scrum practices

  ## UI Component Patterns
  - Navbar Component
    - Logo brand
    - Search Bar: Location, dates, guest count inputs
    - User Menu: Profile avatar, dropdown for account, listings, log out
  - Hero Section Component
    - Background Image or Map: Full-width visual.
    - Search Controls: Centered date picker, guest selector, “Search” button.
  - Filter Bar Component
    - Filter Chips: Price range slider, property type toggles, amenities icons.
    - Sort Dropdown: “Price”, “Rating”, “Newest” options.
  - Property Card Component
    - Image Carousel: Main photo + thumbnails.
    - Title & Location: Short headline + city.
    - Rating & Reviews: Star icon + number of reviews.
    - Price: Nightly rate with “/ night” label.
    - Wishlist Icon: Heart toggle.
  - Property Grid Component
    - Responsive Layout: 1 to 3 columns depending on screen size.
    - Lazy Loading: Load more as you scroll.
  - Property Details Component
    - Image Gallery: Full-screen carousel.
    - Details Panel: Host info, description, amenities list.
    - Booking Sidebar: Date picker, guest count, price breakdown, “Reserve” button.
  - Footer Component
    - Links: About, Help Center, Careers, Privacy.
    - Language/Currency Selector.
    - Social Icons: External links (e.g. Twitter, Instagram).
  - Global Components
     - Toast Notifications: Success/error messages.
     - Loading Spinner: During data fetches.
     - Modal Wrapper: For login/signup and alerts.