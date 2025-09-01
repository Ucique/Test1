# Ucique - Homepage with Blog and Forum

A beautiful, modern website featuring a homepage, blog, and forum with user authentication and role-based access control.

## Features

### 🎨 **Beautiful Design**
- Modern, responsive design with smooth animations
- Multiple selectable themes (Light, Dark, Ocean, Forest, Sunset, Purple, High Contrast, Sepia)
- Floating shapes and parallax effects
- Smooth transitions and hover effects

### 🔐 **User Authentication**
- **Admin Users**: Full access to create articles, moderate forum, and manage content
- **Regular Users**: Can comment on articles and reply to forum threads
- **Guests**: Can read content but cannot modify anything
- Secure password hashing and session management

### 📝 **Blog System**
- Article creation and management (admin only)
- Category-based organization
- Search and filtering capabilities
- Comment system with user authentication
- Responsive article cards with excerpts

### 💬 **Forum System**
- Thread creation and management (admin only)
- Category-based organization
- Search, filter, and sort options
- Reply system with nested conversations
- Thread activity tracking

### 🎯 **Technical Features**
- Pure HTML/CSS/JavaScript (no Node.js required)
- Local storage fallback for development
- MySQL database ready for production
- Responsive design for all devices
- Progressive enhancement

## Setup Instructions

### Prerequisites
- MySQL server running locally
- Web browser with JavaScript enabled

### Database Setup
1. Ensure MySQL is running on your system
2. Create a database called `new_schema`
3. The default credentials are:
   - **Username**: `root`
   - **Password**: `abc123`
   - **Database**: `new_schema`

### Running the Website
1. **Clone or download** the project files to your local machine
2. **Open** `index.html` in your web browser
3. **Navigate** between pages using the navigation menu
4. **Switch themes** using the theme switcher in the top-right corner

### Default Admin Account
- **Username**: `admin`
- **Password**: `abc123`

## File Structure

```
ucique2/
├── index.html          # Homepage
├── blog.html           # Blog page
├── forum.html          # Forum page
├── login.html          # Login/Register page
├── css/
│   ├── main.css        # Main styles and layout
│   ├── themes.css      # Theme definitions
│   └── animations.css  # Animations and effects
├── js/
│   ├── database.js     # Database connection and utilities
│   ├── auth.js         # Authentication and user management
│   ├── main.js         # Homepage functionality
│   ├── blog.js         # Blog functionality
│   ├── forum.js        # Forum functionality
│   └── login.js        # Login page functionality
└── README.md           # This file
```

## Usage Guide

### For Guests
1. **Browse** articles and forum threads
2. **Read** content without restrictions
3. **View** comments and replies
4. **Switch themes** to customize your experience

### For Regular Users
1. **Register** a new account or **login** with existing credentials
2. **Comment** on blog articles
3. **Reply** to forum threads
4. **Search** and **filter** content
5. **Customize** your experience with themes

### For Admin Users
1. **Login** with admin credentials (`admin` / `abc123`)
2. **Create** new blog articles
3. **Create** new forum threads
4. **Moderate** content and comments
5. **Manage** user-generated content

## Theme Options

- **☀️ Light**: Clean, bright interface (default)
- **🌙 Dark**: Easy on the eyes for low-light environments
- **🌊 Ocean**: Calming blue tones
- **🌲 Forest**: Natural green palette
- **🌅 Sunset**: Warm orange and red hues
- **💜 Purple**: Rich purple and lavender
- **⚡ High Contrast**: Maximum accessibility
- **📜 Sepia**: Vintage, warm tones

## Development Notes

### Local Development
- The website uses localStorage as a fallback for development
- No server setup required for basic functionality
- Database queries are simulated locally

### Production Deployment
- Replace localStorage logic with actual MySQL connections
- Update database credentials in `js/database.js`
- Ensure proper server-side security measures

### Browser Compatibility
- Modern browsers with ES6+ support
- Responsive design for mobile and desktop
- Progressive enhancement for older browsers

## Customization

### Adding New Themes
1. Add theme variables to `css/themes.css`
2. Include theme-specific styles for components
3. Add theme button to HTML with appropriate emoji

### Modifying Content
1. Update text content in HTML files
2. Modify categories in JavaScript files
3. Adjust styling in CSS files

### Adding Features
1. Extend JavaScript classes with new methods
2. Add new HTML elements and CSS styles
3. Update database schema if needed

## Troubleshooting

### Common Issues
- **Theme not switching**: Check browser console for JavaScript errors
- **Login not working**: Verify database connection and credentials
- **Content not loading**: Check localStorage and database setup
- **Styling issues**: Ensure all CSS files are properly linked

### Browser Console
- Check for JavaScript errors in the browser's developer tools
- Verify that all files are loading correctly
- Look for database connection errors

## License

This project is created for educational and demonstration purposes. Feel free to modify and use as needed.

## Support

For questions or issues:
1. Check the browser console for error messages
2. Verify all files are in the correct directory structure
3. Ensure MySQL is running and accessible
4. Check browser compatibility and JavaScript settings

---

**Enjoy your new Ucique website!** 🎉
