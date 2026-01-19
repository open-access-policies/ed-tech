# Accessibility Standards Policy (ENG-POL-005)

## 1. Objective

This policy establishes **[Company Name]**'s commitment to accessibility for students, educators, and all users, including those with disabilities. It ensures compliance with the Americans with Disabilities Act (ADA), Section 504 of the Rehabilitation Act, Section 508, and Web Content Accessibility Guidelines (WCAG), enabling equitable access to educational technology.

## 2. Scope

This policy applies to:
- All web applications and websites
- All mobile applications
- All downloadable content and documents
- All user interfaces and experiences
- All workforce members involved in product development

## 3. Policy

**[Company Name]** is committed to providing accessible educational technology that can be used by all students, regardless of ability. Our products meet or exceed applicable accessibility standards.

### 3.1 Accessibility Standards

**3.1.1 Primary Standard: WCAG 2.1 AA**

**[Company Name]** products conform to Web Content Accessibility Guidelines (WCAG) 2.1 Level AA, which requires:

**Perceivable:**
- Text alternatives for non-text content
- Captions and alternatives for multimedia
- Content adaptable to different presentations
- Distinguishable content (sufficient contrast, resizable text)

**Operable:**
- Keyboard accessible
- Sufficient time to read and use content
- No content that causes seizures
- Navigable with clear structure
- Input modalities beyond keyboard

**Understandable:**
- Readable and understandable text
- Predictable operation
- Input assistance and error prevention

**Robust:**
- Compatible with assistive technologies
- Valid, well-structured code

**3.1.2 Additional Standards**

Where applicable, **[Company Name]** also addresses:

| Standard | Applicability | Coverage |
|----------|---------------|----------|
| **Section 508** | Federal contracts; federally-funded schools | Web, software, documents |
| **Section 504** | All recipients of federal funding | Non-discrimination; accommodations |
| **ADA Title II/III** | Educational institutions; places of public accommodation | Accessible services |
| **WCAG 2.2** | Emerging best practices | Additional success criteria |
| **ATAG 2.0** | Authoring tools | Content creation accessibility |

**3.1.3 Conformance Levels**

| Product Area | Target Level | Timeline |
|--------------|--------------|----------|
| **Core educational features** | WCAG 2.1 AA | Current |
| **Administrative features** | WCAG 2.1 AA | Current |
| **New features** | WCAG 2.1 AA | At launch |
| **Legacy features** | WCAG 2.1 AA | Remediation roadmap |
| **Mobile apps** | WCAG 2.1 AA equivalent | Current |

### 3.2 Accessible Design Requirements

**3.2.1 Visual Design**

| Requirement | Standard | Implementation |
|-------------|----------|----------------|
| **Color contrast** | 4.5:1 for normal text; 3:1 for large text | Automated testing; design system |
| **Don't rely on color alone** | Information conveyed by other means | Icons, patterns, labels |
| **Resizable text** | 200% zoom without loss of function | Responsive design; relative units |
| **Focus indicators** | Visible focus state | Consistent focus styling |
| **Motion** | Reduced motion option; no auto-play | Respect prefers-reduced-motion |

**3.2.2 Keyboard Accessibility**

- All functionality available via keyboard
- Logical tab order matching visual order
- No keyboard traps
- Skip navigation links
- Keyboard shortcuts documented (and customizable)

**3.2.3 Screen Reader Support**

- Semantic HTML structure
- ARIA labels where needed
- Alt text for images
- Form labels associated with inputs
- Dynamic content announced appropriately
- Heading hierarchy maintained

**3.2.4 Multimedia Accessibility**

| Content Type | Accessibility Requirement |
|--------------|--------------------------|
| **Video** | Captions (synchronized); audio descriptions for visual content |
| **Audio** | Transcripts |
| **Live events** | Real-time captions where feasible |
| **Interactive media** | Keyboard controls; text alternatives |

### 3.3 Document Accessibility

**3.3.1 PDF Documents**

PDFs provided to schools and users must be:
- Tagged for structure
- Readable by screen readers
- Have logical reading order
- Include alt text for images
- Have accessible forms (if applicable)

**3.3.2 Other Document Formats**

| Format | Accessibility Requirements |
|--------|---------------------------|
| **Word documents** | Heading styles; alt text; accessible tables |
| **PowerPoint** | Slide titles; reading order; alt text |
| **Excel** | Table headers; cell descriptions; named ranges |
| **Web content** | WCAG 2.1 AA compliance |

**3.3.3 User-Generated Content**

For features where users create content:
- Provide guidance on creating accessible content
- Offer accessibility checking tools
- Enable alt text entry for uploaded images

### 3.4 Assistive Technology Compatibility

**3.4.1 Supported Technologies**

**[Company Name]** tests with common assistive technologies:

| Category | Technologies |
|----------|-------------|
| **Screen readers** | NVDA, JAWS, VoiceOver (macOS/iOS), TalkBack (Android) |
| **Voice control** | Dragon NaturallySpeaking, Voice Control (macOS/iOS) |
| **Magnification** | ZoomText, built-in OS magnifiers |
| **Switch access** | Switch Control (iOS), Switch Access (Android) |
| **Alternative input** | Head tracking, eye tracking |

**3.4.2 Browser Support**

Accessibility tested on:
- Chrome (current and previous major version)
- Firefox (current and previous major version)
- Safari (current and previous major version)
- Edge (current and previous major version)

**3.4.3 Mobile Accessibility**

Mobile apps support:
- Platform accessibility features (VoiceOver, TalkBack)
- Dynamic text sizing
- High contrast modes
- Reduced motion settings

### 3.5 Accessibility Testing

**3.5.1 Automated Testing**

- Automated accessibility scans in CI/CD pipeline
- Tools: axe-core, Lighthouse, WAVE
- Automated tests catch ~30-40% of issues
- All pages scanned before release

**3.5.2 Manual Testing**

- Keyboard-only navigation testing
- Screen reader testing (at least 2 readers)
- Cognitive accessibility review
- Manual testing required for complex interactions

**3.5.3 User Testing**

- Include users with disabilities in user research
- Conduct accessibility-focused usability testing
- Gather feedback from accessibility advocates

**3.5.4 Third-Party Audits**

- Annual accessibility audit by qualified third party
- Audit covers representative sample of functionality
- Findings prioritized and remediated
- Results available to schools upon request

### 3.6 Accessibility Documentation

**3.6.1 VPAT (Voluntary Product Accessibility Template)**

**[Company Name]** maintains a current VPAT documenting:
- WCAG 2.1 AA conformance
- Section 508 conformance (where applicable)
- Known limitations and planned remediation

**VPAT is:**
- Updated annually and with major releases
- Available to schools and districts upon request
- Published on company website

**3.6.2 Accessibility Statement**

Public accessibility statement includes:
- Commitment to accessibility
- Standards we target
- How to request accommodations
- How to report accessibility issues
- Contact information

**3.6.3 Accessibility Roadmap**

**[Company Name]** maintains an accessibility roadmap:
- Known issues and planned fixes
- Prioritization based on impact
- Timeline for remediation
- Progress reporting

### 3.7 Accommodation Requests

**3.7.1 Process**

When users or schools request accommodations:
1. Request received by Customer Success or accessibility contact
2. Evaluate request and identify solution
3. Provide accommodation within reasonable timeframe
4. Document accommodation provided
5. Consider for product improvements

**3.7.2 Reasonable Accommodations**

**[Company Name]** provides reasonable accommodations including:
- Alternative formats for content
- Feature configuration for accessibility needs
- Training on accessibility features
- Technical support for assistive technology users

**3.7.3 Response Time**

| Request Type | Response Commitment |
|--------------|---------------------|
| **Urgent (blocking student)** | **[Number, e.g., 24-48]** hours |
| **Standard accommodation** | **[Number, e.g., 5]** business days |
| **Feature request** | Evaluated for roadmap |

### 3.8 Training and Awareness

**3.8.1 Development Team Training**

All product development team members receive:
- Accessibility fundamentals training
- Role-specific accessibility training (design, development, QA)
- Updates on accessibility standards and techniques

**3.8.2 Content Creator Training**

Staff who create content (support docs, marketing) trained on:
- Accessible document creation
- Alt text writing
- Plain language principles

**3.8.3 Ongoing Awareness**

- Accessibility champions in product teams
- Regular accessibility reviews and knowledge sharing
- Accessibility included in definition of done

### 3.9 Procurement and Third Parties

**3.9.1 Vendor Accessibility Requirements**

When procuring third-party components or integrations:
- Request VPAT and accessibility documentation
- Evaluate accessibility as part of selection criteria
- Include accessibility requirements in contracts
- Ensure third-party content meets standards

**3.9.2 Integration Accessibility**

Third-party integrations must:
- Not introduce accessibility barriers
- Maintain keyboard accessibility
- Work with assistive technologies
- Provide accessible documentation

## 4. Standards Compliance

| Requirement | Citation | [Company Name] Control |
|-------------|----------|------------------------|
| Web accessibility | WCAG 2.1 AA | This policy Section 3.1 |
| Federal contractor accessibility | Section 508 | This policy Section 3.1.2 |
| Non-discrimination | Section 504; ADA | This policy Sections 3.7 |
| Accessible educational materials | IDEA; state laws | This policy Section 3.3 |
| VPAT documentation | Industry standard | This policy Section 3.6 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **WCAG** | Web Content Accessibility Guidelines, developed by W3C |
| **VPAT** | Voluntary Product Accessibility Template, documenting conformance |
| **Assistive Technology** | Hardware or software that helps people with disabilities use technology |
| **Section 508** | Federal accessibility requirements for information technology |
| **Section 504** | Federal law prohibiting disability discrimination in federally-funded programs |
| **ARIA** | Accessible Rich Internet Applications, specifications for web accessibility |
| **Alt Text** | Alternative text describing images for screen reader users |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Product Management** | Include accessibility in requirements; prioritize accessibility work |
| **UX/Design** | Design accessible interfaces; conduct accessibility reviews |
| **Engineering** | Implement accessible code; fix accessibility bugs |
| **QA** | Test for accessibility; validate fixes |
| **Content Team** | Create accessible documents and content |
| **Customer Success** | Handle accommodation requests; communicate accessibility features |
| **Legal/Compliance** | Advise on legal requirements; review VPATs |

## 7. Related Documents

- ENG-POL-001: Secure Software Development Policy
- ENG-POL-004: Age-Appropriate Design Policy
- ENG-PROC-008: Accessibility Testing and Remediation Procedure
- ANNEX-008: VPAT Template

## 8. Policy Review

This policy is reviewed annually and upon:
- Updates to WCAG guidelines
- Changes to Section 508 or related regulations
- Significant accessibility audit findings
- Major product changes

**Policy Owner:** **[Role Title, e.g., VP of Product]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
