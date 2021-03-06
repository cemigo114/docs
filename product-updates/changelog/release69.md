# Release 6.9

## Changelog 6.8

| New Feature | Improvement | Bug Fix | Enterprise Only |
| :---: | :---: | :---: | :---: |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28154%29.jpg) | ![](../../.gitbook/assets/improvement%20%2819%29%20%28349%29.jpg) | ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2817%29.jpg) | ![](../../.gitbook/assets/enterprise%20%2818%29%20%2816%29%20%281%29%20%2815%29.jpg) |

### Scribe

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28257%29.jpg) | Improve email subject for canceled order |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2814%29.jpg) | \[P0\]Cancel feature for Order owner |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28313%29.jpg) | Task form should select "All Inputs" by default |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28448%29.jpg) | Create Task button is incorrectly locked due to missing inputs |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2841%29.jpg) | Embed Model Version Id Missing in classification annotation requests |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28167%29.jpg) | Detection Annotations with Predictions display out of order |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28737%29.jpg) | Can only view app owner annotations when viewing an app as a collaborator |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28736%29.jpg) | Fix Detection Annotations displayed as collaborator bug |

### Spacetime

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28645%29.jpg) | Clicking the x on search item in explorer grid view for search across apps does not properly clear the url |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28240%29.jpg) | Add Min Search Score Range Slider to Search Across Apps Tab |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28162%29.jpg) | Clicking a video search result does not seek to the corresponding timestamp |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2843%29.jpg) | Search By Region button on video thunbnails |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2886%29.jpg) | Clicking see all within image details sidebar of the visual search across apps should render all of the search results in explorer's asset grid view |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28160%29.jpg) | clicking see all from image details sidebar opens refine search search bar in explorer's asset grid view |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28161%29.jpg) | Add getSeekedVideoFrame onMouseOver to visual search results of |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2867%29.jpg) | Add video timestamps to video search results within the |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28165%29.jpg) | Add search across apps to Image View righthand sidebar |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2882%29.jpg) | Add select app in "Refine Search" righthand sidebar |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28125%29.jpg) | Search for annotation.status in Explorer search bar. |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28120%29.jpg) | Search for annotation.user\_id in Explorer search bar. |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28483%29.jpg) | Change Annotation Search To say "filter by" |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28590%29.jpg) | Users having the same name as a collaborator causes annotation searching to break. |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2811%29.jpg) | Manually typing annotation search crashes explorer |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28487%29.jpg) | Endless error if a search fails in explorer |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28391%29.jpg) | Search grid view in explorer gets stuck with old results |

### Enlight

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28165%29.jpg) | Tracker evals: support for original coordinates |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2853%29.jpg) | Integrate MORSE metrics and AP to tracker eval pipeline |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28462%29.jpg) | Cleanup trackers' interface |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28212%29.jpg) | Platform-aware triton orchestrator |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28428%29.jpg) | Connect tracker evaluations with the servicer |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28329%29.jpg) | Implement first version of tracking eval |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28226%29.jpg) | Add embed\_model\_version\_id to cluster and KNN model types |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28234%29.jpg) | Show ROC AUC even if 0.0 |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28313%29.jpg) | crop model carriers forward concepts and other things but shouldn’t. |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2859%29.jpg) | Edit model doesn't work in model details page and app details page |

### Mesh

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28141%29.jpg) | Create pubic Visual Text Recognition workflow |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28106%29.jpg) | \[Portal\] Use only\_base parameter when choosing base workflow |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28232%29.jpg) | Display model name in Selected model row in workflows edit page |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28554%29.jpg) | Remove workflows creation discrepancy |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28188%29.jpg) | Workflows nodes being set as Loading |

### Portal

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28126%29.jpg) | Add Transform, Resize and Drag functionality to canvas rectangles |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28229%29.jpg) | Create CollabpsableBox block to provide app-wide reusable accordion boxes with menu items |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28227%29.jpg) | Create a central entities factory for app-wide entities like annotations to be shared across modules like Explorer and Labeler |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28168%29.jpg) | Mouse leave preserves the FE generated thumbnail of a video at a specific time. |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%28152%29.jpg) | Set up end to end testing framework & write auth tests |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2835%29.jpg) | Create Data mode design |
| ![](../../.gitbook/assets/new_feature%20%281%29%20%281%29%20%2837%29.jpg) | Filter annotations by user id in explorer |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%2868%29.jpg) | re-position data-mode in sidebar |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28464%29.jpg) | Fix Development Environment Crashing on Portal |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28492%29.jpg) | Add responsiveness capability to Portal |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28259%29.jpg) | user can set a unique user\_id \( username \) in profile |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28343%29.jpg) | Enable HTML links for mode-switching icons |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28219%29.jpg) | Remove Upload from Explorer in favor of data mode |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28299%29.jpg) | Memoize video thumbnail urls |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%2845%29.jpg) | Fetch Tag icon data for Explorer inputs on hover |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28440%29.jpg) | Toast notifications should always be on top |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28153%29.jpg) | Refactor Data mode |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28558%29.jpg) | Refactor Data mode \(Upload component\) |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28494%29.jpg) | Remove Detection options dropdown menu |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28200%29.jpg) | Better Toast Notification System |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28175%29.jpg) | Update `ModelVersionSelector` component to make use of `reselect` |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28458%29.jpg) | Add create\_at date to explorer single input view. |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28267%29.jpg) | Expose geo coordinates just like metadata. |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28365%29.jpg) | Add input\_fields and output\_fields columns to model selection view \(from the ModelType\) |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28100%29.jpg) | Migrate model details page to model mode |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28482%29.jpg) | Copy button for personal access tokens doesn't work |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2894%29.jpg) | /models API request being made with appId as undefined |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2848%29.jpg) | hovering over inputs keeps fetching annotations even if fetched once |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28261%29.jpg) | Fix incorrect check for 'isDetectionModel' throughout Portal |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28651%29.jpg) | Broken TypeScript configuration for Cypress and Jest |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28673%29.jpg) | TypeScript type-checks not running on build/push |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2857%29.jpg) | Data Mode crashing due to legacy string refs |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%28575%29.jpg) | Predictions don't show up if you reload on Explorer input |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2896%29.jpg) | Metrics view doesn't work anymore |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2870%29.jpg) | Classification Annotations not loading |
| ![](../../.gitbook/assets/bug%20%28196%29%20%28452%29%20%2887%29.jpg) | Model filter app name resets when you click ctrl/alt key |

### API

| Status | Details |
| :--- | :--- |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28323%29.jpg) | \[API Client Tests Javascript\] Fail fast when `stage` is invalid |
| ![](../../.gitbook/assets/improvement%20%2819%29%20%28266%29.jpg) | Don’t treat StatusCode\_FEATUREFLAG\_BLOCKED errors as server errors |

