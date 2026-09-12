---
title: ""
summary: 'Personal academic portfolio of Chompunick "AnnAnn" Chieng, an Electrical and Computer Engineering undergraduate at CUHK-Shenzhen exploring robotics, embedded systems, hardware, and software.'
date: 2026-09-12
type: landing

sections:
  # ============================================================
  # HERO / ABOUT ME
  # ============================================================

  - block: resume-biography-3
    content:
      username: me
      text: |
        I'm an Electrical and Computer Engineering undergraduate at
        CUHK-Shenzhen exploring robotics, hardware, and software.

        I enjoy learning how the different parts of a robotic system work
        together — from circuits and embedded systems to programming,
        perception, and control.

        I'm currently building my technical foundation and looking for
        opportunities to gain more hands-on experience in robotics research.

      button:
        text: View My GitHub
        url: https://github.com/nAnAowob

      headings:
        about: About Me
        education: Education
        interests: Research Interests

    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md

      avatar:
        size: medium
        shape: circle

  # ============================================================
  # RESEARCH INTERESTS
  # ============================================================

  - block: markdown
    id: research
    content:
      title: "🤖 Research Interests"
      subtitle: "Exploring robotics from both hardware and software perspectives"
      text: |
        I'm currently exploring several areas of **robotics and intelligent
        systems** as I build my undergraduate technical foundation.

        ### 👁️ Robot Perception

        I'm interested in how robots understand their surroundings through
        cameras, sensors, computer vision, localization, and SLAM.

        ### 🦾 Robot Control & Manipulation

        I'm interested in how robots move and interact with the physical
        world, including motion, control systems, robotic manipulators, and
        autonomous systems.

        ### ⚡ Embedded Robotics

        I'm interested in the connection between robotics hardware and
        software, including microcontrollers, sensors, circuits, embedded
        systems, and hardware-software integration.

        ### 🪰 Bio-Inspired Robotics

        My previous research internship introduced me to robotics inspired by
        biological systems through a mayfly-inspired robotics project.

        I'm still exploring these directions rather than specializing in one
        area yet. My goal is to gain experience through coursework, personal
        projects, and research before deciding which direction I want to
        pursue more deeply.

    design:
      columns: "1"

  # ============================================================
  # RESEARCH EXPERIENCE
  # ============================================================

  - block: markdown
    id: research-experience
    content:
      title: "🔬 Research Experience"
      subtitle: "My first step into robotics research"
      text: |
        ## Bio-Inspired Robotics Research Internship

        **VISTEC Robotics Lab · June – July 2025**

        I completed a two-month internship in a bio-inspired robotics
        laboratory, where I gained exposure to a **mayfly-inspired robotics
        project**.

        The experience introduced me to robotic mechanisms, engineering
        experimentation, research workflows, technical documentation, and
        research reporting.

        Rather than treating the internship as the end of a project, I see it
        as the beginning of my interest in robotics research. It motivated me
        to strengthen both my hardware and software foundations and explore
        different robotics research directions.

        [**View Mayfly-Inspired Robotics →**](/projects/mayfly-inspired-robotics/)

    design:
      columns: "1"

  # ============================================================
  # PROJECTS
  # ============================================================

  - block: collection
    id: projects
    content:
      title: "🛠️ Selected Projects"
      subtitle: "Research, programming, and things I am learning"
      text: |
        A selection of projects and coursework documenting my progress in
        robotics, engineering, and programming.

      filters:
        folders:
          - projects

    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: true

  # ============================================================
  # SKILLS
  # ============================================================

  - block: resume-skills
    id: skills
    content:
      title: Technical Skills & Current Learning
      username: me

  # ============================================================
  # CURRENTLY LEARNING
  # ============================================================

  - block: markdown
    id: learning
    content:
      title: "🌱 What I’m Learning Now"
      subtitle: "Building the foundations I need for robotics"
      text: |
        I'm currently strengthening the fundamentals that I will need for
        future robotics research and engineering work.

        **Programming:** C, C++, Python, Git & GitHub

        **Mathematics:** Calculus, Linear Algebra, Probability

        **Engineering:** Circuit Design, Digital Systems, Embedded Systems,
        Sensors

        **Robotics Tools I'm Exploring:** ROS2, OpenCV, Robot Perception,
        SLAM, and Robot Control

        These are areas I'm actively learning and exploring — not areas I
        claim expertise in yet.

    design:
      columns: "1"

  # ============================================================
  # EDUCATION
  # ============================================================

  - block: markdown
    id: education
    content:
      title: "🎓 Education"
      subtitle: ""
      text: |
        ## The Chinese University of Hong Kong, Shenzhen

        **Electrical and Computer Engineering — Computer Engineering Stream**

        Class of 2025 intake · Currently Year 2

        ### Selected Academic Results

        - **MAT1001 Calculus I** — A
        - **CSC1005** — A
        - **CSC1006** — A
        - **ENG1002** — A-
        - **AP Calculus BC** — 5/5

        My current academic focus is building a strong foundation across
        mathematics, programming, computer engineering, circuits, and
        robotics-related subjects.

        ## Kamnoetvidya Science Academy (KVIS)

        **STEM research-based high school**

    design:
      columns: "1"

  # ============================================================
  # LEADERSHIP & UNIVERSITY INVOLVEMENT
  # ============================================================

  - block: markdown
    id: activities
    content:
      title: "🌏 Leadership & Campus Involvement"
      subtitle: "Contributing beyond the classroom"
      text: |
        ### Lead Student Organizer — International Student Activities

        I take a leading role among student organizers in planning and
        coordinating international student activities under the guidance of
        university staff.

        My responsibilities include developing activity concepts, planning
        schedules and event structures, coordinating with other student
        organizers, communicating plans with supervising staff, and helping
        execute activities.

        ### Diligentia Student Coach

        I support freshmen as they transition into university life by
        answering questions, sharing my experience, and helping them adapt to
        CUHK-Shenzhen and Diligentia College.

        ### Student Outreach

        I have experience introducing CUHK-Shenzhen to prospective
        international students and families through campus tours and
        student-focused outreach.

        I also hosted and accompanied the CEO of **CASC (Chinese Abroad Study
        Center Co., Ltd.)** during a campus visit and appeared in a CASC video
        sharing my experience as a CUHK-Shenzhen student and scholarship
        recipient.

        Some prospective students later recognized me from the video when
        visiting campus, showing how student perspectives can help prospective
        students understand university life beyond the information available
        on official webpages.

    design:
      columns: "1"

  # ============================================================
  # RESEARCH OPPORTUNITY
  # ============================================================

  - block: cta-card
    id: contact
    content:
      title: "Interested in Robotics Research"
      text: |
        I'm currently looking for opportunities to gain more hands-on
        experience in robotics research at CUHK-Shenzhen.

        I'm particularly interested in robot perception, control, embedded
        robotics, and hardware-software integration.

        I'm happy to learn, contribute, and build the technical skills
        required by the project.

      button:
        text: Visit My GitHub
        url: https://github.com/nAnAowob

    design:
      card:
        css_class: ""
        css_style: ""
---
