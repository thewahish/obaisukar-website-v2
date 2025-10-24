# Website 2.0 - Obai Sukar Portfolio

<!-- Inherits from MASTER_CLAUDE.md and web-development.md -->

## 🎯 Project Overview
**Type**: Web Development
**Status**: Active
**Domain Module**: `modules/domains/web-development.md`

Standalone single-page portfolio website for Obai Sukar - a creator, engineer, and entrepreneur specializing in sound design/music production and IT consultancy.

## 📋 Project-Specific Overrides

### Agent Pipeline Customization
```
Recommended Pipeline: 0 → 4 → 6 → 7 → 11 → 12
Complexity Level: Moderate
Quality Gates: Core Web Vitals, Canvas Performance, Mobile Responsiveness
```

### Web Development Enhancements
- **Canvas Animation**: Advanced digital rain effect requiring performance optimization
- **Interactive Media**: YouTube playlist player and SoundCloud integration
- **Personal Branding**: Custom gradient color scheme and brand identity
- **Portfolio Showcase**: Dynamic project grid with hover animations

## 🔧 Technical Configuration

### Technology Stack
- **Framework**: Vanilla JavaScript with Canvas API
- **Build Tools**: None (self-contained single file)
- **Deployment**: GitHub Pages or static hosting
- **Testing**: Manual cross-browser testing

### Development Commands
```bash
# Development server
python -m http.server 8000
# or
live-server

# No build process (self-contained)
# No package management (vanilla implementation)
```

### Repository Information
- **GitHub URL**: [To be created in sync phase]
- **Deployment URL**: [To be set up]
- **Documentation**: index.html contains inline documentation

## 🎯 Project-Specific Quality Gates

### Must-Have Checks
- [ ] Canvas animation maintains 60fps
- [ ] Core Web Vitals scores: LCP < 2.5s, FID < 100ms, CLS < 0.1
- [ ] Mobile responsive on all devices (320px+)
- [ ] Cross-browser compatibility (Chrome, Firefox, Safari, Edge)
- [ ] Interactive elements accessible via keyboard
- [ ] Portfolio images optimized and lazy-loaded

### Performance Targets
- **Canvas FPS**: 60fps consistent
- **Initial Load**: < 3 seconds
- **Asset Size**: < 2MB total
- **Mobile Performance**: Lighthouse score > 90

## 📂 File Structure Notes

### Important Files
- **index.html**: Complete website - HTML, CSS, JavaScript all embedded
- **index_backup.html**: Previous version backup
- **Assets/**: Image assets and brand materials
- **mockups/**: Design mockups and references

### Special Considerations
- **Single File Architecture**: All code embedded for portability
- **Canvas Performance**: Digital rain effect must be optimized for mobile
- **Brand Consistency**: Custom color palette throughout all elements
- **Self-Contained**: No external dependencies except Google Fonts

## 🔒 Project-Specific Safety Protocols

### Critical Rules
- **Performance First**: Canvas animations must not impact user experience
- **Brand Accuracy**: Use only verified brand colors and messaging
- **Mobile Compatibility**: Test on actual mobile devices, not just desktop simulation

### Never Do
- ❌ Add external JavaScript dependencies that break self-contained nature
- ❌ Use unverified personal information or achievements
- ❌ Implement features that break mobile performance

### Always Do
- ✅ Test canvas performance on low-end devices
- ✅ Verify all portfolio links and contact information
- ✅ Maintain single-file architecture for easy deployment

## 🎨 Brand/Style Guidelines

### Visual Identity
- **Colors**: 
  - Deep Navy: #292663 (background)
  - Blue: #00AEEF, Pink: #EC008C, Orange: #FBB04C, Purple: #92278F
  - Text Light: #F0F0F0
  - Gradient: Linear combination of blue, pink, orange
- **Fonts**: Poppins (headings), Roboto (body) from Google Fonts
- **Style**: Modern, technical, creative with animated elements

### Content Guidelines
- **Tone**: Professional yet creative, technical expertise with artistic flair
- **Audience**: Potential employers, clients, collaborators in IT and media
- **Message**: Dual expertise in technology and creative arts

## 📊 Success Metrics

### Primary Goals
1. **Professional Presence**: Effective showcase of dual IT/creative expertise
2. **Performance Excellence**: Fast, smooth experience on all devices
3. **Engagement**: Interactive elements encourage exploration

### Measurement Methods
- **Load Speed**: Lighthouse performance audits
- **User Engagement**: Analytics on section interactions
- **Mobile Experience**: Device testing and performance monitoring

## 🔄 Maintenance Notes

### Regular Updates Needed
- **Portfolio Projects**: Add new work examples quarterly
- **Contact Information**: Verify and update as needed
- **Performance**: Monitor and optimize canvas animations

### Known Issues
- **Canvas Battery**: Digital rain effect may impact mobile battery life
- **Single File Size**: Large embedded assets can affect initial load
- **Animation Complexity**: May need performance modes for different devices

## 📞 Stakeholder Information

### Primary Contacts
- **Owner**: Obai Sukar - Personal portfolio and brand representation
- **Technical**: Claude Code - Development and maintenance
- **Content**: Based on verified achievements and portfolio

### Approval Process
1. **Content Review**: Verify all achievements and contact information
2. **Performance Testing**: Cross-browser and device validation
3. **Brand Approval**: Obai's final review and approval

---

## 🔗 Inheritance Chain

```
MASTER_CLAUDE.md (Universal orchestrator)
    ↓
modules/domains/web-development.md (Web-specific patterns)
    ↓
website2.0/CLAUDE.md (Project-specific overrides)
```

### From Master System
- 12-Agent Framework with 0 → 4 → 6 → 7 → 11 → 12 pipeline
- TodoWrite workflow management for multi-step tasks
- Quality gates and performance optimization requirements
- Fact verification for all personal/professional content

### From Web Development Module
- Core Web Vitals optimization and mobile-first approach
- Cross-browser compatibility testing and responsive design
- Performance monitoring and accessibility implementation
- SEO optimization and semantic HTML structure

### Project Overrides
- Canvas animation performance optimization requirements
- Single-file architecture maintenance for portability
- Personal branding color scheme and visual identity
- Interactive media integration with YouTube and SoundCloud

---

*Last Updated: October 2024*
*Version: 2.0*