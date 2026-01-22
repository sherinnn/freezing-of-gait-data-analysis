## Overview

Freezing of gait is an episodic motor impairment commonly observed in Parkinson’s disease. Accurate detection using wearable sensors is challenging due to:
- Severe class imbalance (FoG is rare),
- High inter-subject variability,
- The clinical importance of detecting entire FoG episodes rather than isolated windows.

This project addresses these challenges by:
- Using leave-one-subject-out (LOSO) evaluation,
- Reporting both window-level and episode-level metrics,
- Deriving subject-level endpoints and a composite severity score for patient ranking.

---

## Dataset

- **Dataset**: DAPHNet Freezing of Gait Dataset  
- **Annotations**:
  - `0`: Non-experimental activity (excluded)
  - `1`: Non-FoG activity
  - `2`: Freezing of Gait (FoG)
