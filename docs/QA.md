# Motore Digitale QA Checklist

## Functional

- [ ] Navigation works
- [ ] All internal links work
- [ ] External links work
- [ ] Forms work
- [ ] Phone links work
- [ ] WhatsApp links work
- [ ] Email links work
- [ ] Buttons perform the expected action

## Responsive

Test approximately:

- [ ] 375px
- [ ] 768px
- [ ] 1024px
- [ ] 1440px

Verify:

- [ ] No horizontal overflow
- [ ] No clipped text
- [ ] No broken layouts
- [ ] Navigation works on mobile
- [ ] CTA remains visible and usable

## Visual

- [ ] Consistent spacing
- [ ] Correct typography
- [ ] Correct colors
- [ ] Images correctly cropped
- [ ] No stretched images
- [ ] Hover states work
- [ ] Animations are smooth
- [ ] No visual placeholders remain

## Content

- [ ] No lorem ipsum
- [ ] No fake testimonials
- [ ] No incorrect company information
- [ ] Phone number correct
- [ ] Email correct
- [ ] Address correct
- [ ] CTA copy correct

## SEO

- [ ] Unique page title
- [ ] Meta description
- [ ] Canonical URL
- [ ] Open Graph metadata
- [ ] One H1 per page
- [ ] Correct heading hierarchy
- [ ] Image alt text
- [ ] Sitemap
- [ ] Robots
- [ ] Structured data when relevant

## Performance

- [ ] Images optimized
- [ ] Appropriate image dimensions
- [ ] Lazy loading where appropriate
- [ ] Fonts optimized
- [ ] No unnecessary JavaScript
- [ ] No console errors
- [ ] No obvious layout shifts

## Accessibility

- [ ] Buttons are identifiable
- [ ] Links are identifiable
- [ ] Images have meaningful alt text
- [ ] Form inputs have labels
- [ ] Focus states are visible
- [ ] Text contrast is acceptable
- [ ] Keyboard navigation works for main interactions

## Build

Run:

npm run build

Confirm:

- [ ] Build succeeds
- [ ] No build errors
- [ ] No unexpected warnings

## Production

After deployment:

- [ ] HTTPS works
- [ ] Domain resolves correctly
- [ ] www / non-www behaviour correct
- [ ] All production links work
- [ ] Forms work in production
- [ ] Analytics works if configured
- [ ] Cookie/privacy system works if required
- [ ] Mobile production version checked