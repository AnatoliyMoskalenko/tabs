Табы с возможностью закрытия активного таба.


HTML структура табов:

	<div class="info-header">
		<div class="info-header-tab">#1</div>
		<div class="info-header-tab">#2</div>
		<div class="info-header-tab">#3</div>
	</div>
	<div class="info-tabcontent fade">
		<div class="description">
			Description
		</div>
	</div>
	<div class="info-tabcontent fade">
		<div class="description">
			Description
		</div>
	</div>
	<div class="info-tabcontent fade">
		<div class="description">
			Description
		</div>
	</div>

Вызывается функцией:
tabs('.info-tabcontent', '.info-header', '.info-header-tab');
где:

.info-tabcontent - блок с контентом каждого таба
.info-header - блок с кнопками таба
.info-header-tab - кнопки таба