<template>
  <div class="main-page">

    <div class="page-top bottom">
      <div class="wrapper">
        <div class="breadcrumbs">
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Active</a></li>
            <li>EtherBear #215</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="wrapper wrapper_big">
        <div class="project__body flex">
          <div class="project__left">
            <div class="bottom">
              <div class="project__title">EtherBear</div>
              <div class="project__left-top flex">
                <div class="active-item">Active</div>
                <div class="star star_good flex">
                  <img src="@/assets/img/catalog/star.svg" alt="">
                  <span>8.0</span>
                </div>
                <div class="category category_amber">collectible</div>
              </div>
            </div>
            <div class="project__profile flex bottom">
              <div class="project__avatar img-cover">
                <img src="@/assets/img/project/avatar.jpg" alt="">
              </div>
              <div class="project__profile-box">
                <div class="project__profile-caption">Start date</div>
                <div class="project__profile-date">05-04-2021 3:00PM UTC</div>
              </div>
            </div>
            <div class="timer bottom">
              <div class="timer__caption">before the start</div>
              <div class="countdown">
                <div class="timer__section">
                  <span class="count" id="days"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="hours"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="minutes"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="seconds"></span>
                </div>
              </div>
            </div>
            <div class="project__buttons flex bottom">
              <a href="#" class="project__btn btn btn_blue">
                <div class="btn__caption">site project</div>
                <div class="btn__icon svg-contain">
                  <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M9.33334 1.99967C9.33334 1.63148 9.63182 1.33301 10 1.33301H14C14.3682 1.33301 14.6667 1.63148 14.6667 1.99967C14.6667 2.36786 14.3682 2.66634 14 2.66634H10C9.63182 2.66634 9.33334 2.36786 9.33334 1.99967Z" fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M14 1.33301C14.3682 1.33301 14.6667 1.63148 14.6667 1.99967V5.99967C14.6667 6.36786 14.3682 6.66634 14 6.66634C13.6318 6.66634 13.3333 6.36786 13.3333 5.99967V1.99967C13.3333 1.63148 13.6318 1.33301 14 1.33301Z"
                          fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M13.8047 2.19526C14.0651 2.45561 14.0651 2.87772 13.8047 3.13807L9.13807 7.80474C8.87772 8.06509 8.45561 8.06509 8.19526 7.80474C7.93491 7.54439 7.93491 7.12228 8.19526 6.86193L12.8619 2.19526C13.1223 1.93491 13.5444 1.93491 13.8047 2.19526Z"
                          fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M2.66667 3.33268C2.66667 2.96449 2.96515 2.66602 3.33334 2.66602H7.33334C7.70153 2.66602 8 2.96449 8 3.33268C8 3.70087 7.70153 3.99935 7.33334 3.99935H4.00001V11.9993H12V8.66602C12 8.29783 12.2985 7.99935 12.6667 7.99935C13.0349 7.99935 13.3333 8.29783 13.3333 8.66602V12.666C13.3333 13.0342 13.0349 13.3327 12.6667 13.3327H3.33334C2.96515 13.3327 2.66667 13.0342 2.66667 12.666V3.33268Z"
                          fill="white" />
                  </svg>
                </div>
              </a>
              <a href="#" class="project__btn btn">
                <div class="btn__icon svg-contain">
                  <svg width="13" height="16" viewBox="0 0 13 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M0.833886 9.19109V9.0451C0.855303 8.61317 0.993735 8.19467 1.23491 7.83274C1.63634 7.39798 1.91114 6.86521 2.03048 6.29033C2.03048 5.84601 2.03048 5.39534 2.06929 4.95103C2.2698 2.81195 4.38485 1.33301 6.47404 1.33301H6.52578C8.61497 1.33301 10.73 2.81195 10.937 4.95103C10.9758 5.39534 10.937 5.84601 10.9693 6.29033C11.0903 6.86654 11.3648 7.40097 11.7649 7.83909C12.0079 8.19781 12.1465 8.61478 12.1659 9.0451V9.18474C12.1804 9.76504 11.9805 10.3309 11.6032 10.7779C11.1046 11.3007 10.4281 11.6259 9.70161 11.692C7.57133 11.9205 5.42202 11.9205 3.29175 11.692C2.5661 11.623 1.89051 11.2983 1.39014 10.7779C1.01867 10.3305 0.821496 9.76806 0.833886 9.19109Z"
                          stroke="#3340B4" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                    <path d="M4.86996 13.9014C5.20281 14.3191 5.6916 14.5895 6.22815 14.6527C6.76471 14.7158 7.30478 14.5665 7.72884 14.2378C7.85927 14.1406 7.97663 14.0275 8.07812 13.9014" stroke="#3340B4" stroke-width="1.5" stroke-linecap="round"
                          stroke-linejoin="round" />
                  </svg>
                </div>
                <div class="btn__caption">follow</div>
              </a>
            </div>
            <div class="social-item bottom">
              <div class="social-item__caption">project links</div>
              <div class="social-item__list flex">
                <div class="social-item__coll">
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/mail.svg" alt="">
                      <img src="@/assets/img/project/social/mail-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Email</div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/discord.svg" alt="">
                      <img src="@/assets/img/project/social/discord-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Discord </div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/medium.svg" alt="">
                      <img src="@/assets/img/project/social/medium-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Medium</div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/site.svg" alt="">
                      <img src="@/assets/img/project/social/site-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">site.ru</div>
                  </a>
                </div>
                <div class="social-item__coll">
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/telegram.svg" alt="">
                      <img src="@/assets/img/project/social/telegram-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Telegram <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/instagram.svg" alt="">
                      <img src="@/assets/img/project/social/instagram-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Instagram <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/facebook.svg" alt="">
                      <img src="@/assets/img/project/social/facebook-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Facebook <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/twitter.svg" alt="">
                      <img src="@/assets/img/project/social/twitter-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Twitter <small>(142k followers)</small></div>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="project__right">
            <div class="project__wrap bottom">
              <div class="arrow arrow_prew">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M16.875 10.0002C16.875 9.57833 16.533 9.23633 16.1111 9.23633H3.88889C3.467 9.23633 3.125 9.57833 3.125 10.0002C3.125 10.4221 3.467 10.7641 3.88889 10.7641H16.1111C16.533 10.7641 16.875 10.4221 16.875 10.0002Z"
                        fill="#3340B4" />
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M9.77626 4.11241C9.47794 3.81409 8.99428 3.81409 8.69596 4.11241L3.34874 9.45963C3.05042 9.75795 3.05042 10.2416 3.34874 10.5399L8.69596 15.8872C8.99428 16.1855 9.47794 16.1855 9.77626 15.8872C10.0746 15.5888 10.0746 15.1052 9.77626 14.8069L4.96919 9.99978L9.77626 5.19271C10.0746 4.89439 10.0746 4.41073 9.77626 4.11241Z"
                        fill="#3340B4" />
                </svg>
              </div>
              <div class="arrow arrow_next">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M3.12524 9.99881C3.12524 10.4207 3.46725 10.7627 3.88913 10.7627L16.1114 10.7627C16.5332 10.7627 16.8752 10.4207 16.8752 9.99881C16.8752 9.57693 16.5332 9.23492 16.1114 9.23492L3.88913 9.23492C3.46725 9.23492 3.12524 9.57692 3.12524 9.99881Z"
                        fill="#3340B4" />
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M10.224 15.8866C10.5223 16.1849 11.006 16.1849 11.3043 15.8866L16.6515 10.5394C16.9498 10.2411 16.9498 9.75741 16.6515 9.45909L11.3043 4.11187C11.006 3.81355 10.5223 3.81355 10.224 4.11187C9.92567 4.41018 9.92567 4.89385 10.224 5.19217L15.0311 9.99924L10.224 14.8063C9.92566 15.1046 9.92566 15.5883 10.224 15.8866Z"
                        fill="#3340B4" />
                </svg>
              </div>
              <div class="project__slick">
                <div class="project__slide swiper-slide">
                  <a href="@/assets/img/project/img-1.jpg" class="project__slide-box img-cover" data-fancybox="project">
                    <img src="@/assets/img/project/img-1.jpg" alt="">
                  </a>
                </div>
                <div class="project__slide swiper-slide">
                  <a href="@/assets/img/project/img-2.jpg" class="project__slide-box img-cover" data-fancybox="project">
                    <img src="@/assets/img/project/img-2.jpg" alt="">
                  </a>
                </div>
                <div class="project__slide swiper-slide">
                  <a href="@/assets/img/project/img-3.jpg" class="project__slide-box img-cover" data-fancybox="project">
                    <img src="@/assets/img/project/img-3.jpg" alt="">
                  </a>
                </div>
                <div class="project__slide swiper-slide">
                  <a href="@/assets/img/project/img-2.jpg" class="project__slide-box img-cover" data-fancybox="project">
                    <img src="@/assets/img/project/img-2.jpg" alt="">
                  </a>
                </div>
              </div>
            </div>
            <div class="project__items bottom">
              <div class="project__item">
                <div class="project__item-caption">Min price</div>
                <div class="project__item-desc">$0.01</div>
              </div>
              <div class="project__item">
                <div class="project__item-caption">Max price</div>
                <div class="project__item-desc">$239</div>
              </div>
              <div class="project__item">
                <div class="project__item-caption">Available for sale</div>
                <div class="project__item-desc">1 000 000 tokens</div>
              </div>
            </div>
            <div class="project__row flex bottom">
              <div class="project__coll">
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Website:</div>
                  <a href="#" class="project__coll-link">mariotestino-nft.art</a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Calebrity:</div>
                  <a href="#" class="project__coll-link">Mario Testino</a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Available on:</div>
                  <a href="#" class="project__coll-link">OpenSea.io</a>
                </div>
              </div>
              <div class="project__coll">
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">BlockChain:</div>
                  <a href="#" class="project__coll-info flex">
                    <div class="project__coll-icon">
                      <img src="@/assets/img/project/icon-1.svg" alt="">
                    </div>
                    <div class="project__coll-name">Ethereum (ETH)</div>
                  </a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Platform:</div>
                  <a href="#" class="project__coll-info flex">
                    <div class="project__coll-icon">
                      <img src="@/assets/img/project/icon-2.svg" alt="">
                    </div>
                    <div class="project__coll-name">Dmarket</div>
                  </a>
                </div>
              </div>
            </div>
            <div class="project__article bottom">
              <h2>About</h2>
              <p>The Agoric testnet is a series of global, competitive challenges for validators to prepare, learn, and earn points in advance of Agoric's mainnet. The testnet will consist of five (5) phases, each phase focused on testing a different
                aspect of validating and securing the Agoric blockchain network. Points are earned by completing network and community tasks during each phase, with bonus points awarded to the winners of the challenge tasks. The Agoric testnet is a
                series of global, competitive challenges for validators to prepare, learn, and earn points in advance of Agoric's mainnet. The testnet will consist of five (5) phases, each phase focused on testing a different aspect of validating and
                securing the Agoric blockchain network. </p>
            </div>
            <div class="project__article bottom">
              <h2>Testnet Goals</h2>
              <ol>
                <li>Secure the Network Scale # of validators on our network. Take part in governance and upgrades, and keep the Agoric chain secure.</li>
                <li>Train and Prepare Validators Prepare validators to be ready for mainnet. Learn about the nuances of running a node for mainnet and earn points.</li>
                <li>Grow Community We want to work with the best people from all over the world. A diverse network of validators is the way forward to a strong network.</li>
              </ol>
            </div>
            <div class="project__article bottom">
              <h2>Getting Started</h2>
              <ol>
                <li>Join the <a href="#">Agoric Discord Server</a></li>
                <li>Complete the testnet <a href="#">application form</a> (if you don't have a node yet, more info below)</li>
                <li>If your application is approved, Agoric will send you an email with a link to complete KYC/AML.</li>
                <li>Agoric will then confirm your KYC/AML approval by email.</li>
                <li>Agoric will then give you a unique tag on the Discord giving you access to an incentivized testnet channel.</li>
                <li>You can now (if you haven't) set up your node by following the <a href="#">Validator Setup Guide</a> and add your Public Key into your original application form.</li>
              </ol>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>

</template>
