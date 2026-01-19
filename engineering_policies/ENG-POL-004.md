# Age-Appropriate Design Policy (ENG-POL-004)

## 1. Objective

This policy establishes **[Company Name]**'s requirements for designing products and features that are appropriate for children of different ages. It ensures that products used by minors incorporate age-appropriate privacy protections, interface design, and content safeguards in compliance with COPPA, state laws, and best practices.

## 2. Scope

This policy applies to:
- All products and features used by students under 18
- All user interface and experience design for educational products
- All data collection and privacy settings for minor users
- Product managers, designers, and engineers developing educational products

## 3. Policy

**[Company Name]** designs products with children's best interests in mind, implementing age-appropriate privacy defaults, safety features, and interface design.

### 3.1 Age Group Classifications

**3.1.1 Age Tiers**

Products distinguish between age groups with different requirements:

| Age Group | Classification | Key Considerations |
|-----------|---------------|-------------------|
| **Under 13** | Young Children (COPPA) | Verifiable parental consent; no behavioral ads; enhanced protections |
| **13-15** | Teens (Middle School) | Parental awareness; limited social features; privacy by default |
| **16-17** | Older Teens (High School) | More autonomy; still minor protections |
| **18+** | Adults | Full features available; standard privacy practices |

**3.1.2 Age Verification**

**[Company Name]** determines user age through:
- School-provided roster data (authoritative)
- Account type designation during signup
- Grade level information from school
- Parental account linking for home use

**Neutral Age Verification:**
- Age prompts do not encourage false responses
- No incentive to claim older age
- Date of birth collected neutrally (not "must be 13+")

### 3.2 Privacy by Default

**3.2.1 Default Settings for Minors**

Products default to privacy-protective settings:

| Setting | Default for Minors | Adult Default |
|---------|-------------------|---------------|
| **Profile visibility** | Private/school-only | User choice |
| **Location sharing** | Off | User choice |
| **Contact from strangers** | Blocked | User choice |
| **Search engine indexing** | Off | User choice |
| **Data sharing with third parties** | Minimal/educational only | User choice |
| **Activity tracking** | Educational use only | User choice |

**3.2.2 Opt-In vs. Opt-Out**

For children under 13:
- Privacy-reducing features require opt-in (with parent/school consent)
- Privacy-enhancing features are on by default

For teens 13-17:
- Sensitive features default to off
- High-risk features require additional confirmation

### 3.3 Data Collection Restrictions

**3.3.1 Under-13 Data Collection**

For children under 13 (COPPA):
- Collect only information necessary for educational service
- No collection as condition of participation beyond what's necessary
- No persistent identifiers for behavioral advertising
- No geolocation without explicit school/parent consent

**3.3.2 Teen Data Collection**

For teens 13-17:
- Minimize collection of sensitive categories
- Clear disclosure of data uses
- Easy-to-understand privacy information
- Option to limit personalization

**3.3.3 Prohibited Data Collection**

For all minors, do NOT collect:
- Biometric data (without explicit consent)
- Precise location (unless educationally required)
- Financial information (except for authorized transactions)
- Health data (unless part of contracted services)
- Private communications content (for advertising purposes)

### 3.4 Advertising Restrictions

**3.4.1 Under-13 Restrictions**

For children under 13:
- **No behavioral advertising** based on activity or personal information
- **No targeted advertising** using child's profile
- **No third-party ad networks** that track children
- **Contextual ads only** if any advertising is present

**3.4.2 Teen Restrictions**

For teens 13-17:
- Limit behavioral advertising
- No advertising for age-restricted products (alcohol, gambling, etc.)
- Clear identification of advertising content
- Opt-out from personalized advertising

**3.4.3 Educational Context**

In educational products:
- No advertising that disrupts learning
- School contracts may prohibit all advertising
- Advertising separated from educational content
- No advertising to students in school-contracted services (per SOPIPA)

### 3.5 Interface Design

**3.5.1 Age-Appropriate UI**

Products implement age-appropriate interfaces:

| Element | Under-13 Approach | Teen Approach |
|---------|-------------------|---------------|
| **Language** | Simple, concrete terms | Clear, understandable |
| **Privacy notices** | Child-friendly summaries | Plain language |
| **Settings** | Simplified with guidance | Full options with help |
| **Navigation** | Clear, limited options | More autonomy |
| **Help/support** | Visual, guided | Text + visual |

**3.5.2 Dark Patterns Prohibition**

Products shall NOT use:
- Deceptive design to encourage sharing
- Confusing opt-out processes
- Pressure tactics to change privacy settings
- Hidden data collection
- Manipulative interface elements

**3.5.3 Safety Features**

For minors, include:
- Clear reporting mechanisms for concerns
- Blocking/filtering capabilities
- Adult oversight tools (for parents/teachers)
- Content moderation appropriate to age

### 3.6 Social Features

**3.6.1 Under-13 Social Restrictions**

For children under 13:
- Direct messaging disabled or heavily restricted
- No public profiles
- No contact with unknown adults
- Teacher/parent oversight of communications
- No public posting visible outside school

**3.6.2 Teen Social Features**

For teens 13-17:
- Default to private profiles
- Communication limited to known contacts
- Content moderation active
- Clear community guidelines
- Easy reporting of concerns

**3.6.3 Classroom Communications**

School-facilitated communications:
- Monitored by educators
- Limited to educational purposes
- No private chat with adults outside school oversight

### 3.7 Parental/School Controls

**3.7.1 Parental Dashboard**

For home-use products, parents can:
- View child's activity and progress
- Manage privacy settings
- Receive usage reports
- Request data access or deletion
- Control child's account

**3.7.2 School/Teacher Dashboard**

For school-contracted products, educators can:
- View student progress
- Manage class features
- Control communication settings
- Access only their assigned students

**3.7.3 Control Effectiveness**

- Controls cannot be bypassed by children
- Changes require parent/school authentication
- Children informed of oversight (age-appropriate)

### 3.8 Content Moderation

**3.8.1 User-Generated Content**

For features allowing user content:
- Age-appropriate content policies
- Proactive moderation for harmful content
- Reactive reporting and review process
- Escalation procedures for serious concerns

**3.8.2 AI/Algorithmic Content**

For AI-generated or recommended content:
- Age-appropriate content filtering
- Avoid harmful, inappropriate, or disturbing content
- Human oversight of AI interactions with minors
- Transparency about AI-generated content

### 3.9 Notifications and Engagement

**3.9.1 Notification Limits**

For minors:
- Limit push notifications (especially during school hours)
- No notifications designed to create urgency
- Educational notifications prioritized
- Parent/school control over notifications

**3.9.2 Engagement Design**

Products shall NOT:
- Use addictive design patterns with children
- Gamify in ways that encourage excessive use
- Create fear of missing out (FOMO)
- Pressure continuous engagement

Products SHOULD:
- Support healthy usage patterns
- Provide usage awareness features
- Respect school and home schedules
- Support parent/teacher time limits

## 4. Standards Compliance

| Requirement | Citation | [Company Name] Control |
|-------------|----------|------------------------|
| COPPA online privacy protections | 16 CFR Part 312 | This policy Sections 3.3-3.4 |
| No targeted advertising to children | SOPIPA, state laws | This policy Section 3.4 |
| Age-appropriate design | UK AADC principles | This policy Section 3.5 |
| Default privacy settings | COPPA, best practices | This policy Section 3.2 |
| No dark patterns | FTC guidance | This policy Section 3.5.2 |

## 5. Definitions

| Term | Definition |
|------|------------|
| **Age-Appropriate Design** | Product design that considers the needs and vulnerabilities of users based on their age |
| **Behavioral Advertising** | Advertising targeted based on user behavior, preferences, or personal information |
| **Contextual Advertising** | Advertising based on the content being viewed, not user profile |
| **Dark Patterns** | User interface designs that trick users into doing things they didn't intend |
| **Privacy by Default** | Products configured for maximum privacy without user action |
| **Neutral Age Verification** | Age verification that does not encourage users to provide false information |

## 6. Responsibilities

| Role | Responsibility |
|------|---------------|
| **Student Data Privacy Officer** | Oversee age-appropriate design compliance; review feature releases |
| **Product Management** | Incorporate age-appropriate requirements in product design |
| **UX/Design** | Design age-appropriate interfaces; avoid dark patterns |
| **Engineering** | Implement age-based feature controls; enforce data restrictions |
| **Legal/Compliance** | Advise on COPPA and state law requirements |
| **QA/Testing** | Test age-based features and restrictions |

## 7. Related Documents

- STU-POL-001: Student Data Governance Policy
- PRV-POL-002: COPPA Compliance Policy
- ENG-POL-001: Secure Software Development Policy
- ENG-POL-005: Accessibility Standards Policy
- ENG-PROC-007: Age-Appropriate Design Review Procedure

## 8. Policy Review

This policy is reviewed annually and upon:
- Changes to COPPA regulations or FTC guidance
- New state laws affecting design for minors (e.g., California AADC)
- New product features affecting children
- Industry best practice updates

**Policy Owner:** **[Role Title, e.g., Student Data Privacy Officer]**
**Last Reviewed:** **[Date]**
**Next Review:** **[Date]**
