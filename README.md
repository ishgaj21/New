# New
```mermaid
gantt
    title A Gantt Chart for Lipedema Genetic Research Project
    dateFormat  YYYY-MM-DD
    axisFormat  %d-%m-%Y
    

    section Data <br>Organization
    Organize for Analysis           :org1, 2024-04-25, 9d

    section Bioinformatic Analysis
    Quality Control Checks          :qc1, after org1, 7d
    Variant Calling                 :vc1, after qc1, 14d
    Variant Filtering               :vf1, after vc1, 8d
    Segregation Analysis            :sa1, after vf1, 4d
    Statistical Testing             :st1, after sa1, 5d

    section Database Development
    Design and Develop Database       :dbd1, after st1, 14d
    Database testing and Refinement    : dbr1, after dbd1, 7d
    

    section Thesis Writing
    Drafting of the Thesis          :thw1, 2024-07-01, 9d
    Revision and Peer Feedback      :thw2, after thw1, 5d
    Final Edits and Submission Prep :thw3, after thw2, 3d
