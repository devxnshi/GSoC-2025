<p align="center">
  <img src="files/Intro bg.png" alt="Intro" width="1000"/>
</p>

<div align = "center"><h1>FOSSology UX and UI Redesign </h1>
<h2> <a href = "https://summerofcode.withgoogle.com/programs/2025/projects/gX6omKmk"> GSoC-2025 </a> @ <a href = "https://www.fossology.org/">FOSSology </a> </h2></div>

<p align="center">
	<a href="#project-details">Project Details</a> | 
	<a href="#contributions">Contributions</a> | 
	<a href="#deliverables">Deliverables</a> | 
	<a href="#future-goals">Future Goals</a> | 
  <a href="#key-takeaways">Key Takeaways</a> | 
	<a href="#acknowledgements">Acknowledgements</a>
</p>


<h1 align = "left" id = "project-details">Project Details</h1>

FOSSology is a powerful tool, but its interface doesn’t fully reflect its strengths. Navigation is unintuitive, tasks take longer than needed, and the visual system lacks consistency. My proposal focused on redesigning the interface with usability and accessibility at its core, while also ensuring that components are lightweight and not code-heavy, making them easier for developers to implement and maintain.

To address these challenges, the project began with evaluating the current interface through cognitive testing, heuristic analysis, and accessibility checks. User needs and pain points were then mapped to define redesign requirements, which guided the creation of workflows and high-fidelity mockups reviewed with stakeholders. Alongside this, a design system was established with standardized styles and reusable, lightweight components to ensure consistency, scalability, and ease of contribution.

The goal of this project was not just to modernize the look, but to make FOSSology genuinely easier to use, smoother navigation, reduced cognitive load, and better accessibility across user groups. A cleaner interface and streamlined workflows will help users adopt the tool more easily, while the design system ensures consistency, making it simpler for contributors to maintain and extend for the community’s future growth.

<br>

<h1 align = "left" id = "contributions"> Contributions</h1>


<h2>1. Evaluating the Current Interface </h2>

To begin the redesign, the first step was evaluating FOSSology’s current interface to identify key usability issues. This evaluation combined Cognitive Testing using the VIMM Model to assess user effort in completing tasks, Usability Analysis based on Jakob Nielsen’s Heuristic Principles to detect design and interaction flaws, and Accessibility Analysis following WCAG guidelines to ensure inclusivity in areas such as color contrast, navigation, and form usage. 


<h3>Cognitive Testing - VIMM Model </h3>

Cognitive testing was carried out using the VIMM Model to understand the mental effort required for users to perform common tasks in FOSSology. This approach looked at Visual, Intellectual, Memory, and Motor aspects of interaction, allowing us to see where users were struggling with unnecessary complexity or confusion. 

This helped prioritize redesign areas that directly reduced user friction and cognitive load. 


<h3>Usability Analysis - Jakob Nielsen’s Heuristic Principles</h3>

The interface was also evaluated against Jakob Nielsen’s 10 usability heuristics to uncover design flaws and inconsistencies. Each heuristic such as visibility of system status, error prevention, consistency, and user control was systematically reviewed against existing workflows.

Heuristic evaluation provided a comprehensive picture of where the interface broke common usability standards, giving a clear foundation for improvement.


<h3>Accessibility Analysis - Web Content Accessibility Guidelines (WCAG)</h3>

An accessibility review was conducted using WCAG standards to ensure the interface supported a diverse range of users. This included checking color contrast for readability and accessibility. The analysis showed that while FOSSology was functional, it had accessibility gaps that limited inclusivity. 

Addressing these gaps ensured the redesign would support broader adoption and better accessibility

<br>
<h2>2. User Research and Redesign Requirements </h2>

The project focused on identifying key users, their primary tasks, and the pain points they faced with the existing interface. These insights were then categorized by impact (high, medium, low) and converted into structured redesign requirements and design recommendations, ensuring that the most critical issues were resolved first while leaving room for iterative improvements.


<br>
<h2>3. Creating Workflows and High-Fidelity Screens </h2>

The design process began with translating the defined requirements into low-fidelity wireframes or by recreating the current UI with updated components to explore possible solutions. These were then refined into high-fidelity screens for feedback and review, followed by clickable prototypes that showcased improved workflows and interface elements in practice. 

<h3> How the Redesigned Screens Improve the Current UI and UX</h3>

- The redesigned screens feature a modern visual style with consistent typography, spacing, colors, and custom icons, creating a cleaner and more cohesive interface.
- Navigation is simplified with clearer hierarchy and structure, making it easier for users to find features and complete tasks efficiently.
- Data-heavy pages such as tables and lists are optimized with better organization, filtering, and search options for quicker interpretation.
- Redesigned components are lightweight in terms of CSS, reducing complexity and load time without compromising functionality.
- A new custom icon set was created to match the design system, improving clarity while giving the tool a distinct visual identity.
- Consistent use of design patterns and reusable components across pages reduces confusion and learning effort.
- Accessibility is improved through better contrast, more legible typography, and scalable layouts.

<br>
<h2>4. Established a Design System </h2>

The design system was developed by standardizing typography, colors, spacing, and iconography to establish a cohesive visual identity across the platform. Reusable UI components were created to maintain consistency and reduce development effort, while also ensuring that the interface remained lightweight and easy to implement. This approach not only improved the overall user experience but also provided scalability, making future enhancements more efficient and enabling contributors to extend the system with clarity and consistency.


<h3>Icons</h3>
Custom icons were designed from scratch to align with the style of the new components, adding to the overall coherence of the system. These icons were licensed under CC BY 4.0, meaning they can be freely used in personal or commercial projects with visible credit: “Icons by Devanshi.”

<h4> Pull Request </h4>
<ul>
<li> <a href = "https://github.com/fossology/FOSSologyUI/pull/316"> Icons set 1 </a> </li>
<li> <a href = "https://github.com/fossology/FOSSologyUI/pull/329"> Icons set 2 </a> </li>
</ul> 

<br>

<h1 align = "left" id = "deliverables">Deliverables</h1>


<h3>Establishment of a Cohesive Design System</h3>

| Tasks   | Planned | Status     | Link / Comment    |
| :---       |    :----:   |    :---:      |    :---      |
| Standardize elements such as colors, typography, and spacing for a unified aesthetic.     | Yes       | Completed | <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-28338&t=bOhce5XVHOjbSZh6-0">Design System on Figma </a>  |
| Go through already designed pages and redesign (If necessary).     | Yes       | Completed | Reviewed existing pages, noted observations, and identified what to retain and what to redesign. |


<h3>List of Pages that Needs a Focus</h3>

| Pages   | Planned | Status     | Link / Comment    |
| :---       |    :----:   |    :---:      |    :---      |
| Search     | Yes       | Completed | <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26265">Search pages on Figma </a>  |
| Conf     | Yes       | Completed |  <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26270&t=bOhce5XVHOjbSZh6-0">Conf pages on Figma </a>  |
| Show Jobs     | Yes       | Completed | <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26268&t=bOhce5XVHOjbSZh6-0">Show Jobs pages on Figma </a>  |
| Export List     | Yes       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26271&t=bOhce5XVHOjbSZh6-0">Export List pages on Figma </a>  |
| Copyright/email/url/ECC/IPRA     | Yes       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-27581&t=bOhce5XVHOjbSZh6-0"> Copyright/ECC/IPRA pages on Figma </a>  |
| Folder (Create/edit/delete)     | Yes       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-27582&t=bOhce5XVHOjbSZh6-0">Folders pages on Figma </a>  |
| Group (Create/Edit/Manage)     | Yes       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-27583&t=bOhce5XVHOjbSZh6-0">Group pages on Figma </a>  |
| Obligations (Create/Edit/Manage)     | Yes       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-27584&t=bOhce5XVHOjbSZh6-0">Obligations pages on Figma </a>  |
| License (Create/Edit/Manage)     | Yes       | Completed | <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-27586&t=bOhce5XVHOjbSZh6-0">License pages on Figma </a>  |
| Schedule an Analysis page     | Extra       | Completed | <a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26267&t=bOhce5XVHOjbSZh6-0"> Schedule an Analysis pages on Figma </a>  |
| Upload a New file     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-26266&t=bOhce5XVHOjbSZh6-0">Upload a New file pages on Figma </a>  |
| Upload (Delete/Edit/Move or Copy)     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-28336&t=bOhce5XVHOjbSZh6-0">Upload pages on Figma </a>  |
| License Compatibility Rules     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1333-28337&t=bOhce5XVHOjbSZh6-0">License Compatibility Rules pages on Figma </a>  |
| Duplicate Bucketpool     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1240-25592&t=bOhce5XVHOjbSZh6-0">Duplicate Bucketpool page on Figma </a>  |
| Fossdash Configuration     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1240-25607&t=bOhce5XVHOjbSZh6-0">License Fossdash Configuration page on Figma </a>  |
| Acknowledgements     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1241-25863&t=bOhce5XVHOjbSZh6-0">Acknowledgements page on Figma </a>  |
| Standard License Comments     | Extra       | Completed |<a href = "https://www.figma.com/design/1tBj1VZsqQo9JewRYMm8tX/Fossology-Redesign?node-id=1241-25897&t=bOhce5XVHOjbSZh6-0">Standard License Comments page on Figma </a>  |
| Datatable Redesign     | Yes       | In Progress | Redesign covers multiple pages and considers diverse use cases for a scalable solution.  |
| File View     | Yes       | In Queue | -  |
| License Browser     | Extra       | In Queue | -  |


<br>

<h1 align = "left" id = "future-goals">Future Goals</h1>

1. Finalize the designs for the File View and File Browser pages by first recreating them with the new components, then refining them as per design requirements.
2. Progress with designing additional miscellaneous pages to ensure complete coverage of the FOSSology tool.
3. Conduct structured usability testing with a wider user base to validate designs and get feedback.
4. Continue documenting design decisions and evolving usage guidelines to better support future contributors.
5. Continue collaboration with developers to streamline handoff and maintain design–development consistency.

<br>

<h1 align = "left" id = "key-takeaways">Key Takeaways</h1>

- Understood the importance of a scalable design system with reusable components and consistent styling.
- Gained experience in designing lightweight, developer-friendly components that ease implementation and maintenance.
- Learnt how ongoing stakeholder feedback during design clarified dependencies and guided feature decisions effectively.
- Understood the balance between modernization and retaining familiarity to reduce disruption for existing users.
- Appreciated the role of open-source contribution and community-driven improvements.
- Learnt how to manage time, adaptability, and prioritization while handling multiple redesign tasks across complex workflows.
  
<br>

<h1 align = "left" id = "acknowledgements">Acknowledgements</h1>

I would like to sincerely thank my mentors [Katharina Ettinger](https://www.linkedin.com/in/katharina-ettinger-82055019/), [Shaheem Azmal M MD.](https://www.linkedin.com/in/shaheem-azmal-m-md-71604429/), [Gaurav Mishra](https://www.linkedin.com/in/gmishx/), and [Kaushlendra Pratap](https://www.linkedin.com/in/kaushl2208/) for their constant support, guidance, feedback, and encouragement throughout this project. They were always patient in clarifying my doubts, guiding me through complex features and dependencies, and going the extra mile to ensure I fully understood the intricacies of the system.

I would also like to thank [Amit Nair](https://www.linkedin.com/in/amit-nair/) and [Aditya Khosla](https://www.linkedin.com/in/adityakhosla3/) for their valuable inputs and feedback whenever I encountered blockers or uncertainties in design, which helped me move forward with greater clarity.

I am also really grateful to the FOSSology community and the Google Summer of Code program for providing this incredible opportunity to contribute and grow. The collaborative spirit, constructive feedback, and encouragement from everyone involved made this journey not only a valuable learning experience but also a truly enjoyable one. I look forward to continuing as an active part of the FOSSology community and contributing further to the broader open-source ecosystem. This experience has inspired me to keep learning, sharing, and building together.

<br>

<h1>Reach Out to Me </h1>

- [Connect with me on LinkedIn](https://www.linkedin.com/in/devanshi-sachan-b26487235/)
- [Give a follow on GitHub](https://github.com/devxnshi)
- [Email](devs221102@gmail.com)

