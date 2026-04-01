# 30DayListings.com

**The BLK Group 30 Day Listing Strategy Landing Page**

## Overview
Lead capture page for The BLK Group's 30 Day Listing program:
- As low as 3% total commission
- No 6-month contracts
- No cancellation fees
- Proven 30-day marketing strategy

## Features
- Ultra-minimal black/gold parallax design
- Stats showcase (1000+ homes, Pinnacle Diamond Award, Best Realtors)
- Lead capture form with pricing analysis checkbox
- Supabase integration → Routes to Lab dashboard
- Mobile responsive
- SEO optimized

## Form Fields
- Name
- Email Address
- Property Address
- Desired Timeline to Move
- Price Desired
- Checkbox: Complimentary Pricing Analysis

## Tech Stack
- GitHub Pages hosting
- Supabase backend (thirty_day_leads table)
- Parallax scrolling (desktop only)
- No build process - pure HTML/CSS/JS

## Deployment

### 1. Create GitHub Repo
Repository: `BrandonBLKGroup/30DayListings.com`

### 2. Enable GitHub Pages
- Settings → Pages
- Source: Deploy from branch
- Branch: main
- Folder: / (root)
- Custom domain: 30daylistings.com
- Enforce HTTPS: ✅

### 3. Configure DNS (Namecheap)
**A Records:**
```
@ → 185.199.108.153
@ → 185.199.109.153
@ → 185.199.110.153
@ → 185.199.111.153
```

**CNAME Record:**
```
www → brandonblkgroup.github.io
```

### 4. Create Supabase Table
Go to: https://supabase.com/dashboard/project/fzlwkbhpsklsgkinwljt/sql/new

Paste SQL from: `/Users/jarvis/.openclaw/workspace-spartan4/thirty-day-leads-schema.sql`

### 5. Add Lab Dashboard Tab
Add "30 Day Leads" tab in TheBLKGroupLab.com to view all submissions.

## Files
- `index.html` - Main landing page
- `og-image.jpg` - Social share preview image
- `lpt-logo.jpg` - LPT Realty logo for banner
- `CNAME` - GitHub Pages custom domain config
- `README.md` - This file

## Live URL
https://30daylistings.com

## Contact
Brandon Bruning - The BLK Group at LPT Realty
(479) 857-5994
