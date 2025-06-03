<script>
</script>

<ul class="nav nav-tabs" id="docTab" role="tablist">
	<li class="nav-item" role="presentation">
		<button
			class="nav-link active"
			id="details-tab"
			data-bs-toggle="tab"
			data-bs-target="#details-tab-pane">Реквизиты</button
		>
	</li>
	<li class="nav-item" role="presentation">
		<button
			class="nav-link"
			id="attachments-tab"
			data-bs-toggle="tab"
			data-bs-target="#attachments-tab-pane">Вложения</button
		>
	</li>
</ul>
<div class="tab-content" id="docTabContent">
	<div class="tab-pane fade show active" id="details-tab-pane">
        <div class="form-floating mb-3 w-25">
            <input class="form-control" id="floatingInput">
        </div>
	</div>
	<div class="tab-pane fade" id="attachments-tab-pane">
		<button class="btn btn-sm btn-secondary">Добавить</button>
		<table class="table table-sm table-hover">
			<thead>
				<tr>
					<th>Важное</th>
					<th>Наименование</th>
					<th>Дата создания</th>
					<th>Автор</th>
				</tr>
			</thead>
		</table>
	</div>
</div>
