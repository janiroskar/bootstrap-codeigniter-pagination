bootstrap-codeigniter-pagination
================================

Bootstrap - CodeIgniter Pagination - Config

- Bootstrap v3.2.0
- CodeIgniter v2.1.4, 2.2.0, 3..

		$config['base_url'] = base_url().'/xxx/xxx/xxx';
		$config['total_rows'] = $this->xxxx_model->xxxxx_list_num();
		$config['per_page'] = '10';
		$config['num_links'] = '10';
		$config['uri_segment'] = 4;
		//$config['page_query_string'] = TRUE;
		$config['use_page_numbers'] = TRUE;
		$config['query_string_segment'] = 'page';
		 
		$config['full_tag_open'] = '<ul class="pagination">';
		$config['full_tag_close'] = '</ul><!--pagination-->';
		 
		$config['first_link'] = '&laquo; First';
		$config['first_tag_open'] = '<li>';
		$config['first_tag_close'] = '</li>';
		 
		$config['last_link'] = 'Last &raquo;';
		$config['last_tag_open'] = '<li>';
		$config['last_tag_close'] = '</li>';
		 
		$config['next_link'] = 'Next &rarr;';
		$config['next_tag_open'] = '<li>';
		$config['next_tag_close'] = '</li>';
		 
		$config['prev_link'] = '&larr; Previous';
		$config['prev_tag_open'] = '<li>';
		$config['prev_tag_close'] = '</li>';
		 
		$config['cur_tag_open'] = '<li class="active"><span>';
		$config['cur_tag_close'] = '<span class="sr-only">(current)</span></span></li>';
		 
		$config['num_tag_open'] = '<li>';
		$config['num_tag_close'] = '</li>';
