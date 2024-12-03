# Visualizations - Auditory Hallucination Analysis

## 1. Response Score Distribution
```
Participant Response Scores (0-5 scale)
┌────────────────────────────────────────┐
P6  █████  5/5
P4  ████   4/5
P1  █      1/5
P2  ░      0/5
P3  ░      0/5
P5  ░      0/5
P7  ░      0/5
└────────────────────────────────────────┘
Legend: █ = 1 point, ░ = no response
```

## 2. Processing Mode Interaction
```mermaid
graph TD
    subgraph Success Pathway
        AUTO[Automatic Processing] --> EXT[External Perception]
        EXT --> SUCC[Successful Experience]
        EMO[Emotional Integration] --> SUCC
        CULT[Cultural Integration] --> SUCC
    end
    
    subgraph Barrier Pathway
        ANAL[Analytical Processing] --> RT[Reality Testing]
        RT --> FAIL[Experience Failure]
        KNOW[Prior Knowledge] --> FAIL
        META[Meta-awareness] --> FAIL
    end
```

## 3. Experience Component Heatmap
```
Component Presence Across Participants
           P1  P2  P3  P4  P5  P6  P7
External   ░   ░   ░   █   ░   █   ░
Internal   █   █   █   █   █   █   █
Volume     █   ░   █   █   █   █   ░
Emotion    ░   ░   ░   █   ░   █   ░
Visual     ░   █   █   ░   █   ░   ░
Analysis   █   █   █   ░   █   ░   █
Memory     ░   ░   ░   █   ░   █   ░

Legend: █ = Present, ░ = Absent
```

## 4. Success Factor Impact
```
Factor Impact on Auditory Hallucination
┌────────────────────────────────────────┐
│ Automatic Process  ████████████  High  │
│ Emotion/Memory     ████████      Med   │
│ Cultural Context   ███████       Med   │
│ Visual Imagery     ██            Low   │
│ Analysis          ░░░░          Neg   │
└────────────────────────────────────────┘
```

## 5. Experience Generation Model
```mermaid
graph TD
    subgraph Input Layer
        SUGG[Suggestion]
    end
    
    subgraph Processing Layer
        AUTO[Automatic Processing]
        ANAL[Analytical Processing]
        EMO[Emotional Processing]
    end
    
    subgraph Integration Layer
        INT[Internal Representation]
        EXT[External Perception]
        BOUND[Boundary Navigation]
    end
    
    subgraph Output Layer
        EXP[Experience]
    end
    
    SUGG --> AUTO & ANAL & EMO
    AUTO --> BOUND
    ANAL --> INT
    EMO --> EXT
    BOUND & INT & EXT --> EXP
```

## 6. Individual Response Profiles
```
P4 (High Responder)
├── Automaticity:   ████████░░ 80%
├── Emotion/Memory: ████████░░ 80%
├── Reality Test:   ██░░░░░░░░ 20%
└── Analysis:       █░░░░░░░░░ 10%

P7 (Low Responder)
├── Automaticity:   █░░░░░░░░░ 10%
├── Emotion/Memory: ░░░░░░░░░░ 0%
├── Reality Test:   ████████░░ 80%
└── Analysis:       █████████░ 90%
```

## 7. Boundary Navigation Model
```mermaid
graph LR
    subgraph Internal Domain
        INT[Internal Song]
        SING[Mental Singing]
    end
    
    subgraph Boundary Space
        NAV[Navigation Process]
        VOL[Volume Control]
    end
    
    subgraph External Domain
        EXT[External Sound]
        HALL[Hallucination]
    end
    
    INT --> NAV
    SING --> NAV
    NAV --> EXT
    VOL --> HALL
```

## 8. Processing Style Distribution
```
                    Processing Style Spectrum
Analytical ←───────────────────────────────→ Experiential
    P7  P5  P3  P2  P1        P4  P6
```

## 9. Theme Interaction Web
```mermaid
graph TD
    PROC[Processing Mode] <--> BOUND[Boundary Navigation]
    PROC <--> MEAN[Personal Meaning]
    BOUND <--> MEAN
    PROC <--> BEL[Belief System]
    BOUND <--> BEL
    MEAN <--> BEL
```

## 10. Success Pathway Timeline
```
Time →
Pre-suggestion     During              Post-suggestion
│                 │                   │
├─Expectation     ├─Auto Processing   ├─Integration
├─Prior Knowledge ├─Boundary Nav      ├─Reality Test
├─Preparation     ├─Memory/Emotion    ├─Reflection
```

## Implementation Notes

1. **Software Requirements**
   - Mermaid.js for flow diagrams
   - D3.js for interactive visualizations
   - Basic HTML/CSS for static displays

2. **Color Scheme**
   - Success: #2ECC71 (Green)
   - Failure: #E74C3C (Red)
   - Process: #3498DB (Blue)
   - Neutral: #95A5A6 (Gray)
   - Background: #ECF0F1 (Light Gray)

3. **Interactive Features**
   - Clickable nodes showing participant quotes
   - Hoverable elements with detailed data
   - Filterable displays by success level
   - Zoomable process diagrams

4. **Accessibility Considerations**
   - High contrast options
   - Pattern alternatives to color
   - Text descriptions
   - Keyboard navigation

Let me know if you'd like me to expand on any of these visualizations or create additional ones for specific aspects of the analysis. 