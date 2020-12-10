---
layout: page
title: education
permalink: /education/
weight: 1
---

#### formal education

<div class="col mt-4">
  <div class="timeline-body">
    {% for item in site.data.formal_education %}
      <div class="timeline-item">
        <div class="content">
        <div class="row">
            <div class="col-2">
                <img src= "{{item.image}}" alt="" width="100%" style="vertical-align:top;margin:-10px 0px">
            </div>
            <div class="col-10">
                <h4>{{ item.institution }}</h4>
                <h5><i>{{ item.qualification }}</i></h5>
                <h6 class="date">{{ item.from }} — {{ item.to }}</h6>
            </div>
        </div>
        <br/>
        {{ item.description }}
        </div>
      </div>
    {% endfor %}
  </div>
</div>

<br/>

#### short courses

<div class="col mt-4">
  <div class="timeline-body">
    <div class="timeline-item">
        <div class="content">
        <div class="row">
            <div class="col-12">
                <h4>UCT Global Citizenship</h4>
                <div>
                    <h5><i>Dialogue and Deliberation for Active Citizenship</i></h5>
                    <h6 class="date">Aug 2020 - Oct 2020</h6>
                </div>
                <div>
                    <h5><i>Citizenship & Social Justice: Activism, Service and Social Change</i></h5>
                    <h6 class="date">Feb 2020 — July 2020</h6>
                </div>
            </div>
        </div>
        </div>
      </div>
    <div class="timeline-item">
        <div class="content">
        <div class="row">
            <div class="col-12">
                <h4> UCT CHED: Multilingualism Education Project</h4>
                <div>
                    <h5><i>Basic Xhosa Communication</i></h5>
                    <h6 class="date">July 2018 - Oct 2018</h6>
                </div>
            </div>
        </div>
        </div>
      </div>
  </div>
</div>