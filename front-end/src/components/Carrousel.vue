<script setup>
import '@salesforce-ux/design-system/assets/styles/salesforce-lightning-design-system.min.css'
</script>

<template>
<div class="slds-carousel">
    <div class="slds-carousel__stage">
      <span class="slds-carousel__autoplay">
        <button class="slds-button slds-button_icon slds-button_icon-border-filled slds-button_icon-x-small" aria-pressed="false" title="Stop auto-play">
          <svg class="slds-button__icon" aria-hidden="true">
            <use xlink:href="@salesforce-ux/design-system/assets/icons/utility-sprite/svg/symbols.svg#pause"></use>
          </svg>
          <span class="slds-assistive-text">Stop auto-play</span>
        </button>
      </span>
      <div class="slds-carousel__panels" style="transform:translateX(-0%)">
        <div id="content-id-127" class="slds-carousel__panel" role="tabpanel" aria-hidden="false" aria-labelledby="indicator-id-130">
          <a href="#" class="slds-carousel__panel-action slds-text-link_reset" tabindex="0">
            <div class="slds-carousel__image">
              <img src="@salesforce-ux/design-system/assets/images/carousel/carousel-01.jpg" alt="Visit App Exchange" />
            </div>
            <div class="slds-carousel__content">
              <h2 class="slds-carousel__content-title">Visit App Exchange</h2>
              <p>Extend Salesforce with the #1 business marketplace.</p>
            </div>
          </a>
        </div>
        <div id="content-id-128" class="slds-carousel__panel" role="tabpanel" aria-hidden="true" aria-labelledby="indicator-id-131">
          <a href="#" class="slds-carousel__panel-action slds-text-link_reset" tabindex="-1">
            <div class="slds-carousel__image">
              <img src="@salesforce-ux/design-system/assets/images/carousel/carousel-02.jpg" alt="Click to Customize" />
            </div>
            <div class="slds-carousel__content">
              <h2 class="slds-carousel__content-title">Click to Customize</h2>
              <p>Use the Object Manager to add fields, build layouts, and more.</p>
            </div>
          </a>
        </div>
        <div id="content-id-129" class="slds-carousel__panel" role="tabpanel" aria-hidden="true" aria-labelledby="indicator-id-132">
          <a href="#" class="slds-carousel__panel-action slds-text-link_reset" tabindex="-1">
            <div class="slds-carousel__image">
              <img src="@salesforce-ux/design-system/assets/images/carousel/carousel-03.jpg" alt="Download SalesforceA" />
            </div>
            <div class="slds-carousel__content">
              <h2 class="slds-carousel__content-title">Download SalesforceA</h2>
              <p>Get the mobile app that&#x27;s just for Salesforce admins.</p>
            </div>
          </a>
        </div>
      </div>
      <ul class="slds-carousel__indicators" role="tablist">
        <li class="slds-carousel__indicator" role="presentation">
          <a id="indicator-id-130" class="slds-carousel__indicator-action slds-is-active" href="#" role="tab" tabindex="0" aria-selected="true" aria-controls="content-id-127" title="Visit App Exchange tab">
            <span class="slds-assistive-text">Visit App Exchange tab</span>
          </a>
        </li>
        <li class="slds-carousel__indicator" role="presentation">
          <a id="indicator-id-131" class="slds-carousel__indicator-action" href="#" role="tab" tabindex="-1" aria-selected="false" aria-controls="content-id-128" title="Click to Customize tab">
            <span class="slds-assistive-text">Click to Customize tab</span>
          </a>
        </li>
        <li class="slds-carousel__indicator" role="presentation">
          <a id="indicator-id-132" class="slds-carousel__indicator-action" href="#" role="tab" tabindex="-1" aria-selected="false" aria-controls="content-id-129" title="Download SalesforceA tab">
            <span class="slds-assistive-text">Download SalesforceA tab</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>