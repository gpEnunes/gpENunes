<div class="gravatar-hovercard"><style></style>
			<div class="gravatar-hovercard__inner">
				<div class="gravatar-hovercard__header-image" style="background: url(&quot;https://1.gravatar.com/userimage/279712575/528ce3ba12e3766957a79d4259b631e5?size=1024&quot;) 50% 42% / 100% no-repeat;"></div>
				<div class="gravatar-hovercard__header">
					<a class="gravatar-hovercard__avatar-link" href="https://gravatar.com/full54cf653697e?utm_source=hovercard" target="_blank">
						<img class="gravatar-hovercard__avatar" src="https://0.gravatar.com/avatar/bf3af42eac85884cf52952103f325e89d00118903c3d2becfbeb7c3db006a834?s=256&amp;d=initials" width="104" height="104" alt="Emerson Nunes">
					</a>
					<a class="gravatar-hovercard__personal-info-link" href="https://gravatar.com/full54cf653697e?utm_source=hovercard" target="_blank">
						<h4 class="gravatar-hovercard__name">Emerson Nunes</h4>
						<p class="gravatar-hovercard__job">Full Stack Developer</p>
						<p class="gravatar-hovercard__location">Coimbra, Portugal</p>
					</a>
				</div>
				<div class="gravatar-hovercard__body">
								<p class="gravatar-hovercard__description">Full-stack developer from Coimbra 🇵🇹 — building things that last.</p>
							</div>
				<div class="gravatar-hovercard__social-links">
					<a class="gravatar-hovercard__social-link" href="https://gravatar.com/full54cf653697e?utm_source=hovercard" target="_blank" data-service-name="gravatar">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/gravatar.svg" width="32" height="32" alt="Gravatar">
					</a>
					
					<a class="gravatar-hovercard__social-link" href="https://www.linkedin.com/in/emerson-nunes5" target="_blank" data-service-name="linkedin">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/linkedin.svg" width="32" height="32" alt="LinkedIn">
					</a>
				
					<a class="gravatar-hovercard__social-link" href="https://github.com/gpEnunes" target="_blank" data-service-name="github">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/github.svg" width="32" height="32" alt="GitHub">
					</a>
				
					<a class="gravatar-hovercard__social-link" href="https://stackoverflow.com/users/32633124/emerson-nunes" target="_blank" data-service-name="stackoverflow">
						<img class="gravatar-hovercard__social-icon" src="https://s.gravatar.com/icons/stackoverflow.svg" width="32" height="32" alt="Stack Overflow">
					</a>
				
				</div>
				
				<div class="gravatar-hovercard__footer">
					<a class="gravatar-hovercard__profile-url" title="https://gravatar.com/full54cf653697e" href="https://gravatar.com/full54cf653697e?utm_source=profile-card" target="_blank">
						gravatar.com/full54cf653697e
					</a>
					<a class="gravatar-hovercard__profile-link" href="https://gravatar.com/full54cf653697e?utm_source=profile-card" target="_blank">
						View profile →
					</a>
				</div>
				
				
				<div class="gravatar-hovercard__profile-color" style="background: rgb(26, 26, 46);"></div>
			</div>
		<script>
		const hovercardInner = document.querySelector('.gravatar-hovercard__inner');

		function openDrawer( target, container ) {
			const selector = '.gravatar-hovercard__drawer[data-drawer-name="' + target.dataset.targetDrawer + '"]';
			const drawer = container.querySelector( selector );
			drawer?.classList.add( 'gravatar-hovercard__drawer--open' );
		}

		function closeDrawer( target, container ) {
			const selector = '.gravatar-hovercard__drawer[data-drawer-name="' + target.dataset.targetDrawer + '"]';
			const drawer = container.querySelector( selector );
			drawer?.classList.add( 'gravatar-hovercard__drawer--closing' );
			drawer?.classList.remove( 'gravatar-hovercard__drawer--open' );

			setTimeout( () => {
				drawer?.classList.remove( 'gravatar-hovercard__drawer--closing' );
			}, 300 );
		}

		hovercardInner.querySelectorAll( '.gravatar-hovercard__button' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => openDrawer( el, hovercardInner ) );
		} );
		hovercardInner.querySelectorAll( '.gravatar-hovercard__drawer-close' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => closeDrawer( el, hovercardInner ) );
		} );
		hovercardInner.querySelectorAll( '.gravatar-hovercard__drawer-backdrop' ).forEach( ( el ) => {
			el.addEventListener( 'click', () => closeDrawer( el, hovercardInner ) );
		} );
	</script></div>
