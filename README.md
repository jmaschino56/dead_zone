# Pitch Profiler’s Iteration of Dynamic Dead Zone

This implementation is inspired by Max Bay’s Dynamic Dead Zone with several key differences:  
- It analyzes all pitch types, not just fastballs.  
- It employs eight distinct LightGBM models to generate the dynamic dead zones.  
- It applies a separate dead-zone selection algorithm (Hungarian Assignment) for each pitch type.  

You can explore Max’s Dynamic Dead Zone [here](https://dynamic-dead-zone.streamlit.app/) and follow him on X [here](https://x.com/choice_fielder).

#### *Copyright Pending*

Under U.S. copyright law, you may:  
- Use the ideas, methods, or procedures behind the work, provided you write your own implementation (e.g., a “clean-room” reimplementation of an algorithm).  
- Independently create a work that is similar in function, as long as you do not copy protected expression.  
- Quote limited excerpts for criticism, commentary, news reporting, scholarship, or research (fair use).  
- Create transformative or parody works that add new expression, meaning, or message (fair use).  
- Reverse-engineer software for interoperability or security research, subject to applicable statutory exceptions (e.g., DMCA provisions).  
- Make archival or backup copies of lawfully acquired works.  
- Perform private viewing, playing, or execution of legitimately acquired software.  
- Link to or embed publicly available code or media, provided you do not distribute the files themselves.  

Under U.S. copyright law, you may **not**:  
- Reproduce source code, object code, documentation, graphics, UI layouts, or other protected expression without authorization.  
- Distribute copies—sell, rent, host, upload, or otherwise make the work publicly available.  
- Prepare derivative works—adapt, translate, modify, or refactor the protected content without permission.  
- Perform or display the work publicly (e.g., demo the app at a paid event or stream the software to an audience) without authorization.  
- Circumvent technological protection measures (DRM) applied to the work.  
- Publish substantial excerpts that together constitute the “heart” of the work absent fair-use justification.  

###### You may use this code, Max’s implementation, or other public implementations of Dynamic Dead Zone (or expected movement) for inspiration, but you may **not** copy the code and sell it as your own.
