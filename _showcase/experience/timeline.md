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
                                <i class="fas fa-robot text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Research Scientist — Multimodal Embodied AI &amp; 3D Perception</h5>
                                <p class="text-muted"><a href="https://www.neubility.co.kr/en" target="_blank">Neubility</a>, Seoul, South Korea (Aug 2025 – Present)</p>
                                <p>Multi-camera 3D perception pipeline on NVIDIA Jetson Orin; 8× inference speedup via TensorRT INT8/FP16; DINOv3-backbone Visual Perception Engine for zero-shot open-vocabulary detection; VLA policy validation in Isaac Sim and CARLA.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-info">
                                <i class="fas fa-cloud text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Machine Learning Engineer — MLOps | Computer Vision</h5>
                                <p class="text-muted">Monitra, United Kingdom (Feb 2025 – Sep 2025)</p>
                                <p>15% robustness improvement and 8× throughput gain via diffusion-model data augmentation + PyTorch-TensorRT. Deployed real-time PRPD fault-detection on Azure Kubernetes with FastAPI, Kafka, MLflow CI/CD.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-info">
                                <i class="fas fa-chalkboard-teacher text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Teaching Assistant — CS492 Special Topics in Computer Science</h5>
                                <p class="text-muted">ISI Lab @ KAIST, South Korea (Mar 2025 – Jun 2025)</p>
                                <p>Graduate-level course; assisted students in autonomous navigation, sensor fusion, and deep learning for robotics.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-success">
                                <i class="fas fa-graduation-cap text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Ph.D. Candidate — Multimodal Autonomous Navigation | Privacy-Preserving ML</h5>
                                <p class="text-muted">Intelligent Service Integration Lab @ KAIST, South Korea (Aug 2021 – Jun 2025)</p>
                                <p>Designed DeepILS and NanoMST neural inertial navigation architectures (sub-meter accuracy, 4.7× compute reduction). Built multi-camera Vision Transformer for 3D object detection and BEV segmentation at 25 FPS on embedded hardware. Engineered ConvXformer with formal ε-DP privacy guarantees. FPGA-based SLAM accelerator at 30 FPS.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-info">
                                <i class="fas fa-laptop-code text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Research Intern — Mobile Robotics | SLAM | Multi-Sensor Fusion</h5>
                                <p class="text-muted">DAIM Lab @ KAIST, South Korea (Nov 2023 – Mar 2024)</p>
                                <p>Engineered industrial AMR integrating SLAM (LiDAR, IMU, wheel odometry) achieving &lt;5 cm positioning error for warehouse navigation.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-primary">
                                <i class="fas fa-microchip text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Senior Manager — SoC Design | FPGA | AI Accelerators</h5>
                                <p class="text-muted">National Electronics Complex (<a href="https://necop.gov.pk/" target="_blank">NECOP</a>), Pakistan (Apr 2019 – May 2022)</p>
                                <p>Led SoC/RTL verification using SystemVerilog/UVM for custom AI accelerator designs; tape-out on first silicon pass for two major programs. Developed optimized FPGA/SoC designs (Verilog, HLS, Vivado HLS) across four production programs.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-primary">
                                <i class="fas fa-satellite text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>Assistant Manager — Satellite Systems | FPGA | Signal Processing</h5>
                                <p class="text-muted">National Space Agency (<a href="https://suparco.gov.pk/" target="_blank">SUPARCO</a>), Pakistan (Oct 2014 – Apr 2019)</p>
                                <p>Designed radiation-tolerant FPGA-based DSP systems for satellite communication with AI-accelerated image compression (&gt;99.9% uptime). Awarded <strong>Distinguished Service Award (2018)</strong>.</p>
                            </div>
                        </div>

                        <div class="timeline-block">
                            <div class="timeline-icon bg-success">
                                <i class="fas fa-user-graduate text-white"></i>
                            </div>
                            <div class="timeline-content">
                                <h5>B.S. Electrical Engineering</h5>
                                <p class="text-muted">University of Engineering and Technology, Taxila (UET), Pakistan (Nov 2010 – Jul 2014)</p>
                                <p>Thesis: <em>Realtime Object Detection and Autonomous Control using 3-DoF Robotic Arm</em></p>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </div>

    <style>
        .timeline { position: relative; margin: 0 auto; }
        .timeline-container { width: 90%; max-width: 1170px; margin: 0 auto; position: relative; }
        .timeline-block { position: relative; margin: 2em 0; }
        .timeline-block:after { content: ""; display: table; clear: both; }
        .timeline-icon {
            width: 40px; height: 40px; border-radius: 50%;
            box-shadow: 0 0 0 4px white, inset 0 2px 0 rgba(0,0,0,.08), 0 3px 0 4px rgba(0,0,0,.05);
            position: absolute; left: 0; top: 0; text-align: center; line-height: 40px;
        }
        .timeline-content {
            position: relative; margin-left: 60px; background: white;
            border-radius: 0.25em; padding: 1em; box-shadow: 0 3px 0 #d7e4ed;
        }
        .timeline-content h5 { margin-top: 0; }
        .timeline-content:before {
            content: ''; position: absolute; top: 16px; right: 100%;
            height: 0; width: 0; border: 7px solid transparent; border-right: 7px solid white;
        }
        @media only screen and (min-width: 1170px) {
            .timeline-content { margin-left: 120px; }
            .timeline-icon { left: 50px; }
            .timeline-container:before {
                content: ''; position: absolute; top: 0; left: 85px;
                height: 100%; width: 4px; background: #d7e4ed;
            }
        }
    </style>
</div>
