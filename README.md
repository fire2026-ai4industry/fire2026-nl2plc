<div style="background-color:#e6f3ff; padding:15px; border-radius:10px;">
  <h3>AI4Industrial Automation: NL2PLC Code Generation and Understanding</h3>
  <ul>
    <li>Registration Opens: TBD</li>
    <li>Training Data Release: TBD</li>
  </ul>
</div>

body {
    background-color: #f5f9ff;
}

Programmable Logic Controllers (PLCs) are specialized industrial computers used to automate real-time control processes in manufacturing plants, power systems, oil & gas pipelines, and other critical infrastructure. PLCs continuously monitor inputs from sensors (e.g., temperature, pressure, switches) and control outputs (e.g., motors, valves, alarms) based on programmed logic.
One of the standard programming languages for PLCs is Structured Text (ST), defined under the IEC 61131-3 standard. ST code is a high-level, Pascal-like programming language that allows engineers to write complex control logic using conditional statements, loops, timers (e.g., TON/TOF), and function blocks.
Unlike general-purpose programming, PLC programs are:

* Time-critical and event-driven
* Closely tied to physical processes and safety constraints
* Required to be highly reliable and deterministic

    
As a result, even small logical errors in ST programs can lead to unsafe operations, equipment damage, or production loss, making correctness and interpretability extremely important.
This shared task focuses on developing a system that can translate Natural Language (NL) descriptions of industrial control logic into syntactically correct and semantically accurate IEC 61131-3 Structured Text (ST) programs.
