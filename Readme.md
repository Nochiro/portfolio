<div class="container">
            <div class="row">
                <div class="apple">
                 <div>
                   <h2>Education</h2>
                   <li>B-Tech in I.T-9.9cgpa</li>
                   <li>HSC-83.5%</li>
                   <li>SSC-89.2%</li>
                 </div>
                 <div>
                     <h2>Work Experience</h2>
                     <li>Content creation Head At ITSA</li>
                   <li>Worked as a Recruitor for Child health Foundation</li>
                 </div>
                 <div>
                    <h2>Skills</h2>
                    <li>C language</li>
                   <li>DSA</li>
                   <li>JAVA & ADV JAVA</li>
                   <li>HTML & CSS</li>
                 </div>
                </div>
            </div>
        </div>

        .gradient-background {
  background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);
  background-size: 180% 180%;
  animation: gradient-animation 18s ease infinite;

}


@keyframes gradient-animation {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}

.icon-square {
  width: 3rem;
  height: 3rem;
  border-radius: 0.75rem;
}

.profile-img {
  border-radius: 50%;
  height: 100px;
}

.apple{
    display: flex;
    gap:180px;
    justify-content: center;
}
d-block mx-lg-auto img-fluid