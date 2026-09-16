# Tabbi QR Code Workflow

## Problem Solved
Users scatter notes across multiple platforms (Apple Notes, Sheets, Docs, sketch books, Calendar, sticky notes, texts to self) and forget where they wrote things. Solution: QR codes on each workbook page create intentional handoff points between paper design and digital management.

## How It Works

### User Flow
1. User designs/sketches/writes on a workbook page (e.g., "Quick Capture Buckets" spread)
2. Scans the QR code on that page with phone
3. QR links to matching entry form in Tabbi dashboard
4. User transfers/enters relevant data digitally via quick-entry form
5. System captures in correct tab/bucket
6. User now has both: paper design reference + digital working system

### QR Code Placement
- Each workbook spread has unique QR code
- Located in corner or footer of page (TBD based on layout)
- Icon/label: "Scan to enter in Tabbi"

### URL Structure
Format: `tabbi.com/pages/[spread-id]`
Examples:
- `tabbi.com/pages/spread-07` (Quick Capture Buckets)
- `tabbi.com/pages/spread-11` (Due Dates)
- `tabbi.com/pages/spread-17` (Urgency Filtering)

## Page Types (Based on Katie's Feedback)

Katie's pain point revealed these core entry scenarios:

### 1. Text/Notes Capture
**Where it comes from:** Apple Notes, Docs, text-to-self
**Form:**
- Tab selector (Work/Finance/Home/Health/Goals)
- Large text area (open-ended)
- Optional: Select if this is a task, reminder, or just a note
- Save & add another button

### 2. Quick Pin/Sticky Note
**Where it comes from:** Digital/paper sticky notes
**Form:**
- One-line title field
- Tab selector
- Optional due date
- Delete/organize easily later

### 3. Calendar/Scheduling
**Where it comes from:** Calendar app entries
**Form:**
- Date picker
- Time slots (optional)
- Recurring pattern selector
- Event title & notes

### 4. Brain Dump/Inbox
**Where it comes from:** General "where do I put this?"
**Form:**
- Minimal structure
- Everything-goes-here bucket
- Sort/organize later

### 5. Sketching/Visual
**Where it comes from:** Physical sketch books
**Form:**
- Photo upload area
- Optional notes/title
- Assign to tab

### 6. Structured Data (Tabular)
**Where it comes from:** Sheets entries
**Form:**
- TBD based on which spreads use this

## Implementation Plan

### Phase 1: Core QR Spreads
Start with spreads that match clear page types:
- Spread 7: Quick Capture (text area form)
- Spread 9: Due Dates (calendar form)
- Spread 15: Status Badges (sticky pin form)
- Spread 17-20: Urgency Filtering (mixed: time context + quick capture)

### Phase 2: Advanced Spreads
Add as workbook content solidifies:
- Sketch/visual pages
- Structured data pages
- Customization spreads

## Why This Matters
- **Not automatic:** Avoids overwhelming automation or duplicate work
- **Not manual:** Users don't transcribe everything twice
- **Intentional:** Reinforces that design happens on paper, management happens digital
- **Teaching point:** Part 1 explains how information moves between formats
