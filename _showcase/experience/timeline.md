---
show: true
width: 12
date: 2025-04-10 00:00:00 +0900
group: Professional Journey
---
<div class="p-4">
    <h4>Academic and Professional Timeline</h4>
    <hr />
    
    <div class="timeline">
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-12">
                    <div class="timeline-container">
                        <div class="timeline-block">
                            <div class="timeline-icon bg-primary">
                                <i class="fas fa-briefcase text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Machine Learning Engineer</h5>
                                <p class="text-muted">Monitra, UK (Mar 2025 - Present)</p>
                                <p>Developing ML pipelines for fault detection in PRPD images with Azure integration</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-info">
                                <i class="fas fa-chalkboard-teacher text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Teaching Assistant</h5>
                                <p class="text-muted">ISI Lab @ KAIST (Mar 2025 - Present)</p>
                                <p>Assisting graduate students in Special Topics in Computer Science (CS492)</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-info">
                                <i class="fas fa-laptop-code text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>PhD Intern</h5>
                                <p class="text-muted">DAIM Lab @ KAIST (Nov 2023 - Mar 2024)</p>
                                <p>Developed industrial autonomous mobile robot with SLAM-based navigation</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-success">
                                <i class="fas fa-graduation-cap text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>PhD Candidate</h5>
                                <p class="text-muted">KAIST, South Korea (Nov 2021 - Present)</p>
                                <p>Researching inertial localization, sensor fusion, and privacy-preserving navigation</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-primary">
                                <i class="fas fa-microchip text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Senior Manager</h5>
                                <p class="text-muted">NECOP, Pakistan (Apr 2019 - Sep 2022)</p>
                                <p>Led SoC/RTL verification and digital IC design optimization</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-primary">
                                <i class="fas fa-satellite text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Assistant Manager</h5>
                                <p class="text-muted">SUPARCO, Pakistan (Oct 2014 - Apr 2019)</p>
                                <p>Designed satellite payloads and high-speed PCBs for space applications</p>
                            </div>
                        </div>
                        
                        <div class="timeline-block">
                            <div class="timeline-icon bg-success">
                                <i class="fas fa-user-graduate text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>B.S. Electrical Engineering</h5>
                                <p class="text-muted">UET Taxila, Pakistan (Nov 2010 - Jul 2014)</p>
                                <p>Thesis: Realtime Object Detection and Autonomous Control using 3-DoF Robotic Arm</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <style>
        .timeline {
            position: relative;
            margin: 0 auto;
        }
        
        .timeline-container {
            width: 90%;
            max-width: 1170px;
            margin: 0 auto;
        }
        
        .timeline-block {
            position: relative;
            margin: 2em 0;
        }
        
        .timeline-block:after {
            content: "";
            display: table;
            clear: both;
        }
        
        .timeline-icon {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            box-shadow: 0 0 0 4px white, inset 0 2px 0 rgba(0, 0, 0, 0.08), 0 3px 0 4px rgba(0, 0, 0, 0.05);
            position: absolute;
            left: 0;
            top: 0;
            text-align: center;
            line-height: 40px;
        }
        
        .timeline-content {
            position: relative;
            margin-left: 60px;
            background: white;
            border-radius: 0.25em;
            padding: 1em;
            box-shadow: 0 3px 0 #d7e4ed;
        }
        
        .timeline-content h5 {
            margin-top: 0;
        }
        
        .timeline-content:before {
            content: '';
            position: absolute;
            top: 16px;
            right: 100%;
            height: 0;
            width: 0;
            border: 7px solid transparent;
            border-right: 7px solid white;
        }
        
        @media only screen and (min-width: 1170px) {
            .timeline-content {
                margin-left: 120px;
            }
            
            .timeline-icon {
                left: 50px;
            }
            
            .timeline-container:before {
                content: '';
                position: absolute;
                top: 0;
                left: 85px;
                height: 100%;
                width: 4px;
                background: #d7e4ed;
            }
        }
    </style>
</div>