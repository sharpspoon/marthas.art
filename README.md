# Martha's Art Website

Repository for https://marthas.art - A website showcasing the artwork of Martha C. Ward.

## Recent Improvements

The following improvements have been made to enhance the website's performance, maintainability, and accessibility:

### HTML Structure and Organization
- Fixed invalid HTML in nav.html (removed duplicate IDs and improper head section)
- Started standardizing CSS classes across gallery pages (using common gallery-image-link and gallery-image classes)
- Added more descriptive alt text to images for better accessibility

### Asset Optimization
- Created a custom site.css file with standardized styles for gallery images
- Standardized library loading by using CDNs for all external libraries (Bootstrap, jQuery, Lightbox)
- Removed unused CSS and JavaScript files (masonry.css and masonry.js)
- Added lazy loading for images to improve page load performance

### Performance and User Experience
- Added modern CSS features like transitions and hover effects
- Implemented accessibility improvements (focus styles, screen reader support)
- Added print styles for better printing experience
- Added dark mode support using prefers-color-scheme media query
- Used content-visibility for better rendering performance

## Recommendations for Future Enhancements

### Short-term Improvements
1. **Complete Class Standardization**: Update all gallery pages to use the new standardized classes (gallery-image-link and gallery-image)
2. **Improve Alt Text**: Add descriptive alt text to all images across the site
3. **Optimize Images**: Compress and resize images to reduce file sizes and improve load times
4. **Remove Unnecessary Scripts**: Only load Lightbox on pages that use it

### Medium-term Improvements
1. **Create Page Templates**: Develop standardized templates for different page types (gallery, article, etc.)
2. **Implement a Header/Footer Component**: Create reusable header and footer components to reduce code duplication
3. **Add Structured Data**: Implement schema.org markup for better SEO
4. **Implement Responsive Images**: Use srcset and sizes attributes for responsive image loading

### Long-term Improvements
1. **Consider a Static Site Generator**: Convert the site to use a static site generator like Jekyll, Hugo, or Eleventy
2. **Implement a Content Management System**: Add a simple CMS for easier content updates
3. **Add Analytics**: Implement privacy-friendly analytics to track user engagement
4. **Improve SEO**: Conduct an SEO audit and implement recommendations

## How to Contribute

1. Clone the repository
2. Make your changes
3. Test thoroughly
4. Submit a pull request with a clear description of your changes
